Vagrantfile - master
Vagrantfile.puppy - puppy node
Vagrantfile.kitty - kityy node

Steps:
* create a folder for each Vagrant file on your host
* remove `.puppy` extension
* create a vagrant box for each
  
```
vagrant up
```

* add the entries int he `/etc/hosts` file on your host machine:

```
10.0.0.2 master
10.0.0.3 puppy
10.0.0.4 kitty
```
you should now ping them and connect via ssh `ssh vagrant@master` to the machines.
