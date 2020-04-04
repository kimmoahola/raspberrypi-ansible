# raspberrypi-ansible

## Setup on Raspberry Pi

    sudo apt-get update
    sudo apt-get dist-upgrade
    sudo pip install -U ansible
    
    # Input vault password
    sudo nano /root/.vault_pass
    
## Run

    sudo ansible-pull -d /root/raspberrypi-ansible -U https://github.com/kimmoahola/raspberrypi-ansible.git --vault-password-file=/root/.vault_pass
