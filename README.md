# Ansible role: composer
Installs dependency Manager for PHP.

## Requirements
None.

## Role Variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|composer_phar_url|String||http://getcomposer.org/composer.phar|
|composer_bin_path|String||/usr/local/bin/composer|

## Dependencies
+ [php](https://github.com/shomatan/ansible-php)

## Example playbook

```yaml
- hosts: all
  roles:
    - { role: composer }
```
