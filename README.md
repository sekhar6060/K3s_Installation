## Prerequisites installation 

#### To install the prerequisites for DOCKER,K3S,CALICO-CNI,HELM3
```shell
$ ansible-playbook -i hosts prerequisites.yml
$ # If logs needed follow below steps 
$ # ansible-playbook -i hosts prerequisites.yml | tee -a ../prerequisites.log
``` 