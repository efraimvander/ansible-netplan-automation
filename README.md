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



## Requisitos

 **Control Node:** Ubuntu, Debian ou WSL, com Python 3 e Ansible instalado 
 **Managed Node(s):** Ubuntu Server 22.04/24.04, SSH activado, utilizador com sudo

---

# Executar o playbook 
ansible-playbook -i inventory/hosts.ini playbooks/netplan.yml



