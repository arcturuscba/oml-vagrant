Para implementar esta VM:

- Editar en el archivo Vagrantfile, el parámetro "public_network" con una IP correcta para su red.
- vagrant up
- vagrant ssh
- añadir nuestra (/home/usuario/.ssh/) clave publica a la VM: vi ~/.ssh/authorized_keys
- vagrant reload
- ansible-playbook main.yml -i inventory
- vagrant reload
- vagrant ssh
