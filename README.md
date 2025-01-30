#Application docker

Ce répo contient une app dockerisée sur wordpress avec une base de données MySQL.

##prérequis

- Docker
- Docker Compose

##setup

1.clone ce répo :

   ```bash
   git clone https://github.com/your-username/wordpress-app.git

2. créer un fichier secrets dans docker_compose/ avec un fichier MySQL_password.txt contenant ton mdp user et un second mysql_root_password.txt et ton mdp root

3. cd docker_compose
   docker compose up -d

