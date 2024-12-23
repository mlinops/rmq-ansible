<!DOCTYPE html>
<html>
<head>    
<h1># k8s</h1>
<div align="center">
    <img src="https://github.com/user-attachments/assets/c9378e87-b17e-4397-a979-a13432807b5f" alt="K8s Image">
</div>

Clone this repository to your virtual machine that is functioning as an Ansible control node.
```
git clone https://github.com/mlinops/k8s-ansible.git
```
Navigate to the project ansible directory.
```
cd ./k8s-ansible/ansible
```
Run the following command to execute ansible playbook.
```
ansible-playbook -i inventory playbook.yml
```
</body>
</html>
