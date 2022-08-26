# MERN ECOMMERCE AMAZON

![amazona](/frontend/public/images/amazona.png)

## Demo Website

- 👉 Heroku : [https://mern-amazona-app.herokuapp.com](https://mern-ecommerce-amazon.herokuapp.com)

### 1. Clone repo

```
$ git clone https://github.com/delmond147/mern-ecommerce-amazon.git
$ cd mern-ecommerce-amazon
```

### 2. Create .env File

- .env in backend folder

### 3. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - In .env file update MONGODB_URI=mongodb://localhost/amazona
- OR Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - In .env file update MONGODB_URI=mongodb+srv://your-db-connection

### 4. Run Backend

```
$ cd backend
$ npm install
$ npm start
```

### 5. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 6. Seed Users and Products

- Run this on browser: http://localhost:5000/api/seed
- It returns admin email and password and 6 sample products

### 7. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

## Support

- Contact Developer: [Delmond](mailto:delmondbongha147@gmail.com)
