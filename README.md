# What is this repo?

Creating cloud-init user-data.iso for Vagrant and Virtualbox.  
This -> https://portal.cloud.hashicorp.com/vagrant/discover/fantasia/ubuntu64_2404ja

# Configured

* time zone -> Asia/Tokyo
* apt sources.list -> ftp.udx.icscoe.jp
* user & pswd & other -> [Hashicorp Docs](https://developer.hashicorp.com/vagrant/docs/boxes/base)
    * user & pswd -> vagrant
    * authorized_keys -> https://github.com/hashicorp/vagrant/blob/main/keys/vagrant.pub

# Dir explanation

```
README.md # this file
src
└user-data.txt # user-data.iso source file
dist
└user-data.iso # artifacts
```
