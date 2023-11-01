
# Proje Başlığı

This project is a todo-app-pern project created using ansible, terraform and docker.

## Ortam Değişkenleri

To run this project you will need to add the following environment variables to your .env file

- User infos are kept on postgreSQL database on backend. You should create a PostgreSQL container and a password for default user postgres. You don't need to create a different user for postgreSQL. 

- To handshake nodejs container and postgreSQL database container, before creating nodejs image, you have to fill the necessary places ".env" file under server folder. This file is very important to connect database and nodejs backend server. 

- To handshake react server and nodejs server, before creating react image, you have to fill the necessary places ".env" file under client folder. This file also is very important to connect nodejs backend server and react frontend server. 

  
## Bilgisayarınızda Çalıştırın

Projeyi klonlayın

```bash
  git clone https://github.com/kezvur/ansible_todo_pern_proje.git
```

Klonlanan dosyanın içindeki main.tf çalıştırın

```bash
  terraform init
  terraform apply
```
Remote uzantısı ile ansible Control Node bağlanın

Diğer adımlar için Solution of Ansible Project.md adlı dosyadaki maddeleri takip edin.
```

![Uygulama Ekran Görüntüsü](https://github.com/kezvur/ansible_todo_pern_proje/blob/main/todo_web.png)

## Kullanılan Teknolojiler

**Client:** React, 

**Server:** Node, Express

**Database:** Postgresql
 
**infrastructure:** Ansible-Docker-Terraform 
  
## Geri Bildirim

vural93keziban@gmail.com

keziban@kezibanvural.com
  
