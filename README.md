Backend id deployed on render https://backend-1-z63r.onrender.com


### Clone the Repository
```sh
git clone <repository-url>
```

### Install Dependencies


#### Backend
```sh
npm install
```

### Environment Variables
Create a `.env` file in the `Backend` directory and add the following variables:
```
PORT=8080
FRONTEND_PORT=http://localhost:5173
DEV_FRONTEND_PORT=http://localhost:5173
RENDER_FRONTED_PORT=http://localhost:5173
MONGO_URI=mongodb+srv://jaihoguruji29:<Password>@myproject.pf7kbs5.mongodb.net/?retryWrites=true&w=majority&appName=Myproject
or Create a localhost db mongodb://localhost:27017/cnnct
SESSION_SECRET=bdfjfhvbdbjfkbabbp932gubfeql
SALT=10
NODE_ENV=development
```

### Start MongoDB
Ensure MongoDB is running before starting the application:
```sh
mongod
```

### Start the Backend Server
```sh
npm run dev
```
