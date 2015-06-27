Ansible role: packer
=========

An Ansible role that install Hashicorps Packer

Requirements
------------

On the host must `unzip` being installed.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

	packer_version: 0.8.0

The version which should be installed.

	packer_sha256sum: 74b21580a7734fd6a025cfbba5ec60b85a61cd7c99ffe87904c4c013c801e6d2

The sha256sum of the downloaded zip file.

	packer_arch: amd64

Architecture which should be used.

	packer_download_cache: /var/cache/packer.zip

Destination where the zip file should be cached.

	packer_path: /opt/packer

Path where Packer should be installed

	packer_info: /opt/packer/info.txt

Info file where the version is being stored

Dependencies
------------

None

Example Playbook
----------------

    - hosts: buildservers
      roles:
         - { role: craneworks.packer, packer_version: 0.8.0, packer_sha256sum: 74b21580a7734fd6a025cfbba5ec60b85a61cd7c99ffe87904c4c013c801e6d2 }

License
-------

CC-BY - https://creativecommons.org/licenses/by/3.0/
