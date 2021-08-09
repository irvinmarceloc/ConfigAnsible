# ConfigAnsible
## Comandos útiles
### Obtener la lista de todas las varaibles que del servidor 
> ansible localhost -m setup|grep -e ansible_hostname -e ansible_fqdn 
