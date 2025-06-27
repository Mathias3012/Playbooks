# Playbooks de Ansible para AWX

Este repositorio contiene playbooks de Ansible para usar con AWX.

## Playbooks disponibles:

### hello-world.yml
Un playbook simple de ejemplo que:
- Muestra un mensaje de saludo
- Muestra la fecha y hora actual
- Crea un archivo de prueba en /tmp/

### Cómo usar:

1. Configura este repositorio como fuente de control en AWX
2. Crea un proyecto apuntando a este repositorio
3. Crea un Job Template usando uno de los playbooks
4. ¡Ejecuta el job!
