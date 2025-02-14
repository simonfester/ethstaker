### Ethstaker

Install Homebrew on OSX

brew --version

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew update

brew install ansible

brew install hudochenkov/sshpass/sshpass

ansible --version

ansible localhost -m ping --connection=local

ansible-playbook -i hosts.ini os_config.yml --ask-pass --ask-become-pass
