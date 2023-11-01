
# Project Title

To_do Pern Project

## The Purpose of the project
![Uygulama Ekran Görüntüsü](https://github.com/kezvur/ansible_todo_pern_proje/blob/main/ansible.png)
This project is a todo-app-pern project created using ansible, terraform and docker.

## Used technologies

**Client:** React, 

**Server:** Node, Express

**Database:** Postgresql
 
**infrastructure:** Ansible-Docker-Terraform 
  
## Environment Variables

To run this project you will need to add the following environment variables to your .env file

- User infos are kept on postgreSQL database on backend. You should create a PostgreSQL container and a password for default user postgres. You don't need to create a different user for postgreSQL. 

- To handshake nodejs container and postgreSQL database container, before creating nodejs image, you have to fill the necessary places ".env" file under server folder. This file is very important to connect database and nodejs backend server. 

- To handshake react server and nodejs server, before creating react image, you have to fill the necessary places ".env" file under client folder. This file also is very important to connect nodejs backend server and react frontend server. 

  
## Run on Your Computer

Clone the project:

```bash
  git clone https://github.com/kezvur/ansible_todo_pern_proje.git
```
Move your key pair to the file you cloned

Run the main.tf file inside the cloned directory:

```bash
  terraform init
  terraform apply
```
Connect to the Ansible Control Node using the remote extension.

Follow the steps outlined in the file named "Solution of Ansible Project.md" for further instructions.


![Uygulama Ekran Görüntüsü](https://github.com/kezvur/ansible_todo_pern_proje/blob/main/todo_web.png)



## Feedback

vural93keziban@gmail.com

keziban@kezibanvural.com
  
