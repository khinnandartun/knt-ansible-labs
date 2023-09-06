This Ansible script create the user at remote server (in my example , it is jmp server ) and add private key for monitoring_server logging in and also add ssh config to login easily to another monitoring_server.

To run the ansible ,
- create the file_name with env.yaml by referencing env.yaml.example
- add correct varaible value at env.yaml
- add remote server info and inventory.ini
- in my example , my default ansible config is ansible.cfg and also import default inventory file. You can change your preferable inventory file at run time (or) by changing at default config ( ansible.cfg)
- Run the playbook via command  "ansible-playbook -v create-user.yaml"
