![use packer to create iso with postgresql](https://user-images.githubusercontent.com/37847249/42432851-ac8dfd54-831a-11e8-80ca-5c82eff75b2e.jpg)

******
## Packer Ubuntu Vagrant Box with PostgreSQL Pre Installed 




### Agenda:
##### Provisioning of PostgreSQL with Packer & Vagrant

#### Use Case:
##### Automated provisioning of the PostgreSQL through Packer.


#### Tools Used:
- [Packer Hashicorp](https://www.packer.io/intro/index.html)
- [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
- [Ubutnu 18.04.iso with Checksum type SHA256](http://releases.ubuntu.com/18.04/)
- [Vagrant](https://www.vagrantup.com/intro/index.html)
- [PostgreSQL](https://www.postgresql.org/about/)


## Packer Template
![use packer to create iso with dtr_packer template](https://user-images.githubusercontent.com/37847249/42431751-3e7566e0-8315-11e8-9c1f-40760d5b550a.jpg)
> Here showing an example of packer template with builders, provisioners and post-processors. Were `Template` is a JSON file containing the build information, `Provisioner` are tools that install software after the initial OS install, `Post-Processors` are Action to happen after image has to built.

#### Overview of above

![use packer to create iso with dtr](https://user-images.githubusercontent.com/37847249/42431616-a570b7c4-8314-11e8-9bcd-9d008c033348.jpg)
****
## Workflow - PostgreSQL with Packer and Vagrant
![use packer to create iso with postgresql-workflow](https://user-images.githubusercontent.com/37847249/42432886-cad950d8-831a-11e8-9d56-6a85a6127478.jpg)

### Author
Lalith Kumar

#### Licence
MIT
