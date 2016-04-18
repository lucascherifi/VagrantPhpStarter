# vagrant-starter
An executable to fastly start a project in a vagrant box

The purpose of this project in to build in a few seconds a vagrant box according your needs.

Usage example :

```bash
vagrant-start myproject mydomain.com --symfony --elk --rabbitmq
```

The command above will init a Vagrant box based on kasifi/phpbox with ansible code to intall a project using Symfony, with rabbitmq and with the ELK stack preconfigured.

Debian: Jessie (latest LTS)
Nginx: 1.8.1 (latest stable on Debian Jessie)

Availables options are:
- --symfony # 2.8 LTS (latest LTS version)
- --nodejs ... (latest LTS version)
- --php # 5.6 (latest stable version on Debian Jessie) - Do not use if --symfony is used
- --elasticsearch # ... (latest stable on Debian Jessie)
- --elk # ... (latest stable on Debian Jessie)
- --mysql # 5.5 (latest stable version on Debian Jessie)
- --rabbitmq ... (latest stable version on Debian Jessie)
