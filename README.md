# todo-tracker-sharer

**Create, Track and Share To-Do lists**
<br><br>
## <u>**Tech Stack**</u>
### **Frontend**
- [Ionic](https://ionicframework.com) or [React Native](https://reactnative.dev)
- [Tailwind CSS](https://tailwindcss.com)

### **API**
- Start with [REST](https://restfulapi.net) and then port to [GraphQL](https://graphql.org)

### **Backend**
- [Deno](https://deno.land)
- [MongoDB](https://www.mongodb.com)
- [Docker](https://www.docker.com)

<br>

## <u>**Getting Started**</u>
<br>

### **Starting the Services:**
```sh
docker-compose up &> out.log & ; tail -f out.log
```
<br>

### **Connecting to mongodb:**
Install mongodb client and connect via:
```sh
mongo localhost:27017
```
OR
Connect via docker container shell
```sh
docker exec -it mongodb bash
```
and then inside the docker shell
```sh
mongo
```
<br>

### **Stopping the Services:**
```sh
docker-compose down
```
