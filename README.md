# ConfigAnsible
## Comandos útiles

### Obtener la lista de todas las varaibles que del servidor 
> ansible localhost -m setup|grep -e ansible_hostname -e ansible_fqdn 
### Verificar sintaxis 
> ansible-playbook --syntax-check create_file.yml 
### Ejecutar playbook
> ansible-playbook install_dictionary_list.yml 

>obs: por razones de seguridad en este repositorio los hosts no están bien configurados