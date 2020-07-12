# Instalação do MongoDB

### Windows

Acessar https://www.mongodb.com/try/download e baixar a versão **MongoDB Community Server**

Criar uma pasta **"data"** e dentro dela outra pasta **"db"** na unidade onde o Mongo foi instalado.

Para iniciar o servidor, acessar a pasta onde estar instalado com CMD/PowerShell. E executar o comando:

``` 
bin\mongod.exe
```

Para iniciar o MongoDB:

``` 
bin\mongo.exe
```

### Mac & Linux

O procedimento é similar, acesse https://www.mongodb.com/try/download e baixar o **.tar.gz**.

Em seguida uma pasta /data/db com as permissões.

``` 
mkdir -p /data/db
chown -R $USER:$USER /data/db
```

Após, descomprimir o arquivo.
Para iniciar o **servidor** e o **mongo**.

``` 
bin\mongod
bin\mongo
```
