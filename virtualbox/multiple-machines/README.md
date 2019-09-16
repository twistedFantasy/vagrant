1. To start only virtual machine which marked as primary(swarm_manager)
```
$ vagrant up
```

2. To start multiple virtual machines
```
$ vagrant up swarm_manager swarm_worker
```

3. To ssh only virtual machine which marked as primary(swarm_manager)
```
$ vagrant ssh
```

4. To ssh selected machine
```
$ vagrant ssh swarm_worker
```

5. To stop all virtual machines
```
$ vagrant halt
```

6. To stop selected machine
```
$ vagrant halt swarm_worker
```

7. To delete all virtual machines
```
$ vagrant destroy
```

8. To delete selected machine
```
$ vagrant destroy swarm_worker
```


Useful resources:
https://www.vagrantup.com/docs/multi-machine/
http://www.thisprogrammingthing.com/2015/multiple-vagrant-vms-in-one-vagrantfile/
