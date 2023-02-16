## :rocket: ansible_mk

Codigo basico para atualizar, configurar equipamentos Mikrotik via Ansible.

- Comando para executar e verificar os logs: <br />
  - ansible-playbook config_redu_dns_mk.yml -i hosts | tee deploy.log
  - sed -n '/PLAY RECAP/,$p' deploy.log
