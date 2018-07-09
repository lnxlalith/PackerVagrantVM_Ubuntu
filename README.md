![use packer to create iso with dtr front](https://user-images.githubusercontent.com/37847249/42431071-1e43b452-8311-11e8-95bc-944535800838.jpg)
******
## Packer Ubuntu Vagrant Box with Docker Registry Pre Installed 


### Agenda:
##### Provisioning of Docker Registry with Packer & Vagrant

#### Use Case:
##### Automated provisioning of the enterprise level Docker Registry through Packer.
##### Registry will be used to store the Docker images.

#### Tools Used:
- [Packer Hashicorp](https://www.packer.io/intro/index.html)
- [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
- [Ubutnu 18.04.iso with Checksum type SHA256](http://releases.ubuntu.com/18.04/)
- [Vagrant](https://www.vagrantup.com/intro/index.html)
- [Docker](https://docs.docker.com/get-started/)
- [Docker Registry Image](https://docs.docker.com/registry/)

## Packer Template
![use packer to create iso with dtr_packer template](https://user-images.githubusercontent.com/37847249/42431751-3e7566e0-8315-11e8-9c1f-40760d5b550a.jpg)
> Here showing an example of packer template with builders, provisioners and post-processors. Were `Template` is a JSON file containing the build information, `Provisioner` are tools that install software after the initial OS install, `Post-Processors` are Action to happen after image has to built.

#### Overview of above

![use packer to create iso with dtr](https://user-images.githubusercontent.com/37847249/42431616-a570b7c4-8314-11e8-9bcd-9d008c033348.jpg)
****
## Workflow - Docker Registry of Packer and Vagrant
![use packer to create iso with dtr-workflow](https://user-images.githubusercontent.com/37847249/42432149-3660635e-8317-11e8-83c4-2a0cebcb3dbd.jpg)

### Author
Lalith Kumar

#### Licence
MIT
