# Pizza Delivery System App - MERN

> Pizza Delivery System App (MERN - MongoDB, Express, React, Node.js) is a comprehensive web application that enables users to customize and order pizzas online. This project showcases end-to-end development, including user authentication, custom pizza creation, payment integration, real-time order processing, admin control, and email notifications.

<br />
<div align="center">
  <p align="center">
    <br />
    <a href="https://github.com/VarshilKothiya/OIBSIP-PIZZA-DELIVERY-APPLICATION">
    <strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/VarshilKothiya/OIBSIP-PIZZA-DELIVERY-APPLICATION">Report Bug</a>
    ·
    <a href=https://github.com/VarshilKothiya/OIBSIP-PIZZA-DELIVERY-APPLICATION>Request Feature</a>
  </p>
</div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

## Live Preview Project

[Live Preview](https://pizza-delivery-system-app-mern-oibsip.vercel.app/)

## Features

- **User Authentication:** Secure registration and login system with JWT tokens for enhanced authorization.
- **Custom Pizza Creation:** Intuitive UI for customizing pizza base, sauce, cheese, and toppings.
- **Payment Integration:** Seamless payment processing using the Razorpay API in test mode.
- **Real-time Order Processing:** Live inventory updates upon order placement for accurate stock management.
- **Admin Control:** Dedicated admin panel for inventory management, order status updates, and notifications.
- **Notifications:** Automated admin email alerts for low inventory levels, ensuring timely restocking.
- **Responsive Design:** User-friendly interfaces designed for various screen sizes.

## Built With

- **Frontend:** React.js (Vite.js) (Tailwind CSS) (React Router) (@reduxjs/toolkit) (React Redux) ()
- **Backend:** Node.js (Express) (bcryptjs) (cors) (dotenv) (express-async-handler) (jsonwebtoken)
- **Database:** MongoDB (Atlas) (Mongoose) (MongoDB Compass)
- **Payment:** Razorpay API (Test Mode)
- **Authentication:** JSON Web Tokens (JWT)
- **Email Notifications:** Nodemailer, SendGrid API
- **Version Control:** Git and GitHub

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) - JavaScript runtime built on Chrome's V8 JavaScript engine
- [NPM](https://www.npmjs.com/) - Node Package Manager

### Installation

1.Clone the repo

```sh
git clone https://github.com/VarshilKothiya/OIBSIP-PIZZA-DELIVERY-APPLICATION
```

2.Install NPM packages

```sh
npm install
```

3.Create a `.env` file in the root directory and add the following

```sh
NODE_ENV = development
PORT = 5000
MONGO_URI = <your_mongodb_uri>
JWT_SECRET = <your_jwt_secret>
SALT = <your_salt>
NODEMAILER_EMAIL = <your_nodemailer_email>
NODEMAILER_PASSWORD = <your_nodemailer_password>
NODEMAILER_SUPERADMIN_EMAIL = <your_nodemailer_superadmin_email>
```

4.Create a `.env` file in the client directory and add the following

```sh
VITE_SERVER_URL = <your_server_url>
VITE_CLIENT_URL = <your_client_url>
```

5.Run the app

```sh
npm run dev
```

## Contributing

Contributions are what make the open-source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the repo
2. Clone the project
3. Create your feature branch (`git checkout -b feature/AmazingFeature`)
4. Commit your changes (`git commit -m "Add some AmazingFeature"`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a pull request



