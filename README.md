# MacOS development environment with Ansible

## Requirements
* [Ansible](https://github.com/ansible/ansible)

## Installation
1. [Install Ansible](http://docs.ansible.com/intro_installation.html)
2. Ensure Apple's command line tools are installed `xcode-select --install`
3. Clone this repository to your local drive
4. Install required Ansible roles `ansible-galaxy install -r requirements.yml`

## Usage

Run ansible playbook and enter your account password when prompted.
```bash
ansible-playbook macos.yml
```

#### App Store only apps
* [Xcode](https://itunes.apple.com/us/app/xcode/id497799835?ls=1&mt=12)
* [GarageBand](https://itunes.apple.com/us/app/garageband/id682658836?mt=12&ls=1)

## Todo

* fish-shell as default shell
* sync sublimetext with dropbox
* terminal setup
* git setup
* nvm
* rbenv
* dotfiles
