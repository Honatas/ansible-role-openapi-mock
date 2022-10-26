OpenAPI Mock Server - Ansible Role
==================================

[![GitHub](https://img.shields.io/github/license/honatas/ansible-role-openapi-mock?style=plastic)](https://github.com/Honatas/ansible-role-openapi-mock/blob/master/LICENSE)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/48203?style=plastic)](https://galaxy.ansible.com/honatas/openjdk_ppa)
[![coffee](https://img.shields.io/badge/buy%20me%20a-coffee-brown?style=plastic)](https://ko-fi.com/honatas "Buy me a coffee")  

Installs any version of OpenAPI Mock Server from [Github](https://github.com/muonsoft/openapi-mock)  

Role Variables
--------------

**download_url** - Path from Github (default: https://github.com/muonsoft/openapi-mock/releases/download)  
**version** - OpenAPI Mock Server version (default: 0.3.3)  
**target_folder** - Folder where you want to install (default: /opt) Note: the folder must exist

Examples
--------

The default installs openapi-mock version 0.3.3 on /opt:
```yaml
roles:
  - honatas.openapi_mock
```

If you want to install another version in another folder:
```yaml
roles:
  - { role: honatas.openapi_mock, version: 0.3.1, target_folder: /app }
```


Requirements
------------

None

Dependencies
------------

None

License
-------

MIT


Contributions
-------------

Feel free to open an issue or add a pull request. Anytime. Really, I mean it.  

Also, if you like my work and want to support me, please consider buying me a [coffee](https://ko-fi.com/honatas).  
