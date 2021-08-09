# ConfigAnsible
## Comandos útiles
### Obtener la lista de todas las varaibles que obtenemos del servidor 
{% filename %}ansible localhost -m setup|grep -e ansible_hostname -e ansible_fqdn{% endfilename %}

