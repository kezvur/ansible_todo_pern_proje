
# Project Title

To_do Pern Project

## The Purpose of the project
![Uygulama Ekran Görüntüsü](https://github.com/kezvur/ansible_todo_pern_proje/blob/main/ansible.png)
This project is a todo-app-pern project created using ansible, terraform and docker.

1. **First Solution:** In this solution, separate YAML files are created for PostgreSQL, Node.js, and React components. These YAML files are executed individually. This approach requires configuring and running each component separately.

2. **Second Solution:** In this solution, a YAML file named "docker_project.yaml" is used. This file serves as a combination of the individual YAML files created in the first solution. This allows all components to be consolidated within a single YAML file, making it easier for deployment.

For more detailed information and explanations, please refer to the "Solution of Ansible Project.md" file, which provides a more comprehensive overview of the project's solutions and implementation steps.

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
  
