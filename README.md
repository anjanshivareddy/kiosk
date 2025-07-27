# Food Self-Order Kiosk

## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:basir/self-order-kiosk
$ cd self-order-kiosk
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/self-order-kiosk  
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection

### 3. Run Backend

```
$ npm install
$ npm run server
```

### 4. Run Frontend

```
# open new terminal
$ npm start
```

### 5. Seed Sample Data

- Open: http://localhost:5000/api/products/seed
- It creates 9 sample products

### 6. Open App

- Open: http://localhost:3000
