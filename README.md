<h1 align="center">Advanced MERN Auth 🔒 </h1>

![Demo App](/frontend/public/screenshot-for-readme.png)

About This Project:

-   🔧 Backend Seperated-(express, dotenv, crypto, cors, cookie-parser, bcryptjs)
-   🗄️ Database Seperated-(mongoose, mongoDB)
-   🔐 Signup Endpoint-(mailtrap)
-   📧 Sending Verify Account Email (only work for mine)
-   🔍 Verify Email Endpoint
-   📄 Build a Welcome Email Template
-   🚪 Logout Endpoint
-   🔑 Login Endpoint
-   🔄 Forgot Password Endpoint
-   🔁 Reset Password Endpoint
-   ✔️ Check Auth Endpoint-(jsonwebtoken)
-   🌐 Frontend Setup-(react-dom, react-hot-toast, axios, zustand, react-router-dom)
-   📋 Signup Page UI-(framer-motion, lucide-react)
-   🔓 Login Page UI
-   ✅ Email Verification Page UI
-   📤 Implement Signup
-   📧 Implement Email Verification
-   🔒 Protecting Our Routes
-   🔑 Implementing Login
-   🏠 Dashboard Page
-   🔄 Implementing Forgot Password
-   🚀 Deployment on Render (Free so take 50sec for first time)

### Setup .env file

```bash
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token
MAILTRAP_ENDPOINT=https://send.api.mailtrap.io/

CLIENT_URL= http://localhost:5173
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
### Extra if Any Error
```
To set NODE_ENV=production in the start script, you need an extra package on a Windows machine: cross-env
Install in the root of the application (so not in the backend or frontend)

npm install cross-env

Then adjust the script:

"scripts": {
"dev": "cross-env NODE_ENV=development nodemon backend/index.js",
"start": "cross-env NODE_ENV=production node backend/index.js",
"build": "npm install && npm install --prefix frontend && npm run build --prefix frontend"
},

Then you can just: run npm start and then everything is accessible under localhost:5000
```
### I'll see you in the next one! 🚀
