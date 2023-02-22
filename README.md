# Project-3: MERN STACK IMPLEMENTATION

## Step 1 - Backend Configuration

`sudo apt update`

`sudo apt upgrade`

`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`

### Install and configure Node.js

`sudo apt-get install -y nodejs`

`node -v`

`npm -v`

### create Todo directory

`mkdir Todo`

`cd Todo`

`npm init`
![Json package](./images/json.jpg)

### InstallexpressJs

`npm install express`

`touch index.js`

`ls`
![index file](./images/touch-index.jpg)

`npm install dotenv`

`touch index.js`

`vim index.js`

`node index.js`

![node-index](./images/index.jpg)

![welcome to express](./images/welcome.jpg)

### create directory for route

`mkdir routes`

` cd routes`

`touch api.js`

`vim api.js`
![api](/images/api.jpg)

### install mongoose DB

`npm install mongoose`

`mkdir models`

`cd models`

`touch todo.js`

`vim todo.js`

`vim api.js`

### Mongodb Database

`touch .env`

` vim .env`

`node index.js`
![database connected](/images/database%20connected.jpg)

### Use Postman to test API

![post](/images/Post.jpg)

![GET](/images/Get.jpg)

![delete record](/images/delete.jpg)

### Frontend creation

` npx create-react-app client`

`npm install concurrently --save-dev`

`npm install nodemon --save-dev`

change directory to client

`cd client`

`vi package.json`

`npm run dev`
![webpack](/images/webpack.jpg)

`npm install axios`
![install axios](/images/axios.jpg)

### Todo App

![todo app](/images/finished-todo.jpg)
