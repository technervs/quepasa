# This his how to install QuePasa with docker

1 - Import the project to a folder

2 - Change the .env.example file to .env

3 - Edit the `.env` with your settings

4 - run the command `docker-compose up -d --build`

# Como instalar o QuePasa com docker

1 - Importe o projeto para uma pasta

2 - Altere o arquivo `docker/.env.example` para `docker/.env`

3 - Edite o `docker/.env` com suas configurações

4 - Faça esta sequência de comandos:

```
docker-compose build
docker-compose up -d
```

ou

```
docker compose build
docker compose up -d
```

ou

```
docker-compose up -d --build
```

# Corrigir erro de banco de dados sqlite

```
docker exec -it $(basename $(pwd))_rails_1 sh -c 'RAILS_ENV=production bundle exec rails c'
```

## 🚀 **Não deixe este projeto morrer, apoie-nos!**

| Se você está desfrutando dos nossos projetos no GitHub e deseja ver mais conteúdo de qualidade, considere fazer uma doação via Pix para apoiar nosso trabalho na comunidade. Sua contribuição nos ajuda a continuar criando soluções inovadoras e mantendo nossos projetos atualizados. Junte-se a nós para construirmos juntos uma comunidade mais forte e sustentável. Obrigado pelo seu apoio! |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

<a href="https://nubank.com.br/pagar/4oyat/OzwgAw9rmW">
  <img src="https://img.shields.io/badge/Chave%20PIX%20Nubank-%23820ad1?style=for-the-badge&logo=nubank&logoColor=white" alt="Chave PIX Nubank" style="border-radius: 4px;">
</a>
