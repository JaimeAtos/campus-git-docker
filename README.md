# campus-git-docker

# Comandos para docker:
docker pull "hello-world"
docker run hello-world

# Comandos para SQLServer
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=P455word" -p 1433:1433 --name sql1 -d mcr.microsoft.com/mssql/server -v C:/SQLServer/data:/var/opt/mssql/data -v C:/SQLServer/log:/var/opt/mssql/log -v C:/SQLServer/secrets:/var/opt/mssql/secrets

# Comandos necesarios para Git
git add .
git commit -m "Realizar cambios"
git push origin master
