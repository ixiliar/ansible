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

# GIT
#### **Tutorial**
```
 https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging
```

#### **clonar este repo**
```
 git clone git@github.com:Turegano/ansible.git
 
 ```
#### **cambiar a rama master**
```
 git checkout master
 
 ```
#### **volver a rama develop**
```
 git checkout develop
 
 ```

