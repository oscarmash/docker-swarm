Instala Docker en los equipos de mi infraestructura

Como se lanza desde el servidor **ansible**
```
ansible-playbook docker-swarm.yml
git add . && git commit -am 'Modificar VM: Swarm.... 1' && git push
```
Se ha de anadir al fichero: vim /etc/ansible/hosts
```
[swarm]
172.26.0.45
172.26.0.46
172.26.0.47
172.26.0.48
172.26.0.49
```
