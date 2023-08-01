## Conectando con el contenedor

```sh
docker-compose exec mongodb bash 
```

## Connect with mongosh

##Docker - Contenedor 
```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```
##Compass - Nube
```sh
 mongosh "mongodb+srv://mateo061299:mateo123@mongodb101.czw29qa.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```