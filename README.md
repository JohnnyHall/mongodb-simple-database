<p align="center">
  <img src="https://i.imgur.com/X6bur7W.png" height='300'/>
</p>

# 🗂️ Mongo-Simple-Database 
> A simple database using MySQL

## 📜 Requirements
1. Docker 20.10 or newer
2. Mongo 4.0.4

## ⚙️ Installation
```
sudo docker pull mongo:4.0.4

sudo docker run -d -p 27017:27017 -v /home/johnnyhall/Mongodb:/Data/db mongo:4.0.4

sudo docker exec -it container_name mongo

db.createCollection('Cars')

db.cars.insertOne({
})

```
## 📝 Mongo Commands
- use teste;
- show dbs;
- db.Cars.find().pretty()
  
## 🌎 Locales
Currently available locales are:
- English (en)

<p align="center">
  Created on <br>
  22/09/2022
</p>
