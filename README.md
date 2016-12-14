# Ansible role: composer
Installs dependency Manager for PHP.

## Requirements
None.

## Supported Platforms
+ EL 7
+ Darwin

## Role Variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|composer_phar_url|String||http://getcomposer.org/composer.phar|
|composer_bin_path|String||/usr/local/bin/composer|

## Dependencies
None.

## Example playbook

```yaml
- hosts: all
  roles:
    - { role: composer }
```
