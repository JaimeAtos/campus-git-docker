# campus-git-docker

# Comandos para docker:
docker pull "hello-world"
docker run hello-world

# Comandos para SQLServer
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=password" -p 1433:1433 --name SQLServer -d mcr.microsoft.com/mssql/server -v C:\Users\a875671\OneDrive - Atos\Escritorio\SQL Server:/var/opt/mssql/data -v C:\Users\a875671\OneDrive - Atos\Escritorio\SQL Server:/var/opt/mssql/log -v C:\Users\a875671\OneDrive - Atos\Escritorio\SQL Server:/var/opt/mssql/secrets

# Comandos necesarios para Git
git add .
git commit -m "Realizar cambios"
git push origin master
