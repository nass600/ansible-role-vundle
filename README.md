# Ansible Role - Vundle

[![Ansible Role](https://img.shields.io/ansible/role/15483.svg)](https://galaxy.ansible.com/nass600/vundle/)
[![GitHub tag](https://img.shields.io/github/tag/nass600/ansible-role-vundle.svg)]()
[![Build Status](https://travis-ci.org/nass600/ansible-role-vundle.svg?branch=master)](https://travis-ci.org/nass600/ansible-role-vundle)
[![Ansible Role](https://img.shields.io/ansible/role/d/15483.svg)](https://galaxy.ansible.com/nass600/powerline/)

Installs Vundle and the Plugins listed on your .vimrc file

# Requirements

You must have your `.vimrc` file already downloaded to your filesystem.

# Role Variables

    vundle_user: ""

User to execute plugins installation

    vundle_config_dir: "~/.vim"

Where to clone all the plugins defined in your `.vimrc`

    vundle_repo: "git://github.com/VundleVim/Vundle.vim.git"

Repo used for Vundle installation


# Dependencies

You must have your `.vimrc` file in your home directory.

# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: nass600.vundle }


## License

[MIT](/src/master/LICENSE)


## Author Information

[Ignacio Velazquez](http://ignaciovelazquez.es)
