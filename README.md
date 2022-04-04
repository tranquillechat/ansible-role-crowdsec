# Crowdsec
This ansible roles installs Crowdsec incl. hub, collections, scenarios, postoverflows, parsers, bouncers and prometheus endpoint.

## Requirements
Tested on:
```yaml
  platforms:
      - name: Ubuntu
        versions:
          - bionic  #16.04
          - focal   #20.04
          - impish  #21.10
      - name: Debian
        versions:
          - bookworm # 11
          - bullseye # 10
```

## how to install.
Clone the repo

## Playbook install crowdsec/bouncer
playbook_crowdsec_debian_install.yaml
ansible-playbook playbook_crowdsec_debian_install.yaml -i hosts.yaml --ask-become-pass

## Playbook install scenario/collection
playbook_crowdsec_debian_install.yaml
$ansible-playbook playbook_crowdsec_debian_install.yaml -i hosts.yaml --ask-become-pass


## Author Information
------------------

[Alf149](https://github.com/alf149) 
