### Ethstaker

Install Ansible OSX

brew --version
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew update
brew install ansible
ansible --version
ansible localhost -m ping --connection=local
ansible-playbook -i hosts.ini os_config.yml


Short Version

create ssh keys
run ansible playbook to configure os first
