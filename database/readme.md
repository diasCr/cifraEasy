# Como instalar

    > $ cd database
    > $ docker-compose up

No Browser copiar o link `http://localhost:8080` e usar os dados para acessar o "adminer":
    
    Sistema: PostgreSQL
    Servidor: db
    Usuário: admin
    Senha: secret

# Como desinstalar

    > $ docker-compose down

# Detalhes

Em caso de mudança nos scripts é necessário refazer o build da "image". A reinstalação do "container" não é suficiente. Para deletar tudo no Docker e reiniciar, utilize o commando:
    
    > $ docker system prune -f -a --volumes   