# Ansible Netplan Automation

Automação Ansible para padronizar e configurar Netplan em servidores Ubuntu; elimina configuração manual e inconsistências de rede.

---

##  Objectivo

Este repositório fornece um **role Ansible reutilizável** para configurar networking em servidores Ubuntu**.

Ao utilizar este role:

- Evita-se retrabalho manual ao configurar Netplan
- Garantem-se configurações consistentes entre múltiplos hosts
- É possível escalar facilmente para dezenas ou centenas de servidores
- Reduz-se risco de erros de YAML ou configuração incorreta

---

##  Estrutura do Repositório
ansible-netplan-automation/
├── README.md
├── ansible.cfg
├── .gitignore
├── inventory/
│ ├── hosts.ini
│ └── group_vars/
│ └── servidores.yml
├── playbooks/
│ └── netplan.yml
└── roles/
└── netplan/
├── defaults/
│ └── main.yml
├── tasks/
│ └── main.yml
├── templates/
│ └── netplan.yaml.j2
└── meta/
└── main.yml

## Requisitos

- **Control Node:** Ubuntu, Debian ou WSL, com Python 3 e Ansible instalado 
- **Managed Node(s):** Ubuntu Server 22.04/24.04, SSH activado, utilizador com sudo

---


