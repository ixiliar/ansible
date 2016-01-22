#Ansible
#### **Instalación de Ansible**
```
sudo pip install ansible
```
#### **Comprobar que se pueden ejecutar módulos de ansible en los nodos**
```
 ansible all -i inventario -m ping -u operacion -k
 ```
#### **Ejecutar comando a la vieja usanza**
```
 ansible host -i  hosts  -m raw -a "cat /etc/hosts" -u usuario -k
 ```
#### **Obtener Facts**
```
 ansible all -i hosts -m setup -u operacion -k
 ```
#### **Lanzar Playbook**
```
 ansible-playbook -i hosts site.yml -k -K
 ```

[Docu Ansible](http://docs.ansible.com/ansible/modules_by_category.html)
