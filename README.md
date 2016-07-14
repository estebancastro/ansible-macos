# MacOS development environment with Ansible

## Requirements
* [Ansible](https://github.com/ansible/ansible)

## Usage

Ensure Apple's command line tools are installed
```bash
xcode-select --install
```

Install required Ansible roles
```bash
ansible-galaxy install -r requirements.yml
```

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
