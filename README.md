# Ansible Role: Artifactory

Ansible role for Artifactory. 

Une fois installé se rendre sur l'interface web.
Se logger avec admin/password
dans Admin -> Configuration -> General Server Name : subdomain.domain.extension
et Custom URL Base http://subdomain.domain.extension

## Requirements

None.

## Role Variables

    # Version of artifactory.
	artifactory_version : 4.4.2

## Dependencies

None.

## Example Playbook

    - hosts: artifactory
      roles:
        - { role: steamulo.artifactory }

## License

MIT

## Author Information

Steamulo - www.steamulo.com
