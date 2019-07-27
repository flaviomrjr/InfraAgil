Máquina: devops
---------------

Procedimentos:
--------------

* **Documentação Ansible**: http://docs.ansible.com/ansible/latest/index.html

* **Like Debian - Ubuntu**
  ```bash
  apt update ; apt install software-properties-common python-pip
  apt-add-repository --yes --update ppa:ansible/ansible
  apt-get install ansible
  ```

* Like RedHat
  ```bash
  yum install epel-release -y
  yum install ansible python python-pip
  ```
