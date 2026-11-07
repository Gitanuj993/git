# Guide to Install git and setup it

## Install Git
refer to : https://git-scm.com/install/

## Create an Account on ``Github`` or ``Gitlab`` etc.
Github : https://github.com

## Setup git and github or access

1. ADD Following Config in Terminal or git bash
   
```bash
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```

2. Generate and Register SSH Key

**Generate Key**: Open your terminal and run ``ssh-keygen -t ed25519 -C "your_email@example.com"``. Press Enter to accept the default file location and optionally set a passphrase. 

**Add to Agent**: Start the SSH agent with ``eval "$(ssh-agent -s)"`` and add your key with ``ssh-add ~/.ssh/id_ed25519``. 
**Copy Public Key**: Display the key using ``cat ~/.ssh/id_ed25519.pub`` and copy the entire output. 
**Register on GitHub**: Log in to GitHub, ``go to Settings > SSH and GPG keys, click New SSH key, paste the copied key, and save.`` 

3. Configure Git Repository

**Test Connection**: Verify the setup by running ``ssh -T git@github.com`` A successful connection confirms authentication. 
Switch to SSH: If your repository was cloned via HTTPS, switch it to SSH by running git remote set-url origin git@github.com:username/repository.git. 
