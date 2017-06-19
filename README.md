# Ansible Role: lets-encrypt

An Ansible role that installs and configures let's encrypt on Fedora.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values:

    lets_encrypt_web_server: ~

### Web server

The service in the variable `lets_encrypt_web_server` will be reloaded in the post hook of the certbot.

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
        - { role: mjanser.lets-encrypt }

## License

MIT
