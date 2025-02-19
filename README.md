
# Full Stack AI SaaS Application – Text-to-Image Generation (AI Illustrate)



## Project Description:

    AI Illustrate is a full-stack AI-powered SaaS application that allows users to generate high-quality images from text prompts using advanced AI models. The platform integrates a credit-based system with online payment functionality, making it a scalable and monetizable AI solution.

## Features
- AI-Powered Image Generation: Utilizes the Clipdrop API to generate images based on user-provided text descriptions.
- User Authentication: Secure login and account management using MongoDB, Express, React, and Node.js (MERN Stack).
- Credit-Based System: Users are allocated a certain number of credits, which are deducted upon each image generation request.
- Online Payment Integration: Supports payment gateways for purchasing additional credits.
- User Dashboard: Displays generated images, credit balance, and transaction history.
- Responsive UI: Built with React for a seamless user experience across devices.
- Scalability: Can be expanded to support multiple AI models or additional features like image upscaling and style customization.


## Tech Stack

- Frontend: ReactJS, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT-based authentication
- AI Integration: Clipdrop API for text-to-image generation
- Payment Gateway: Razorpay  for online payments


## Run Locally

Clone the project

```bash
  git clone 
```

Go to the project directory

```bash
  cd Expense-Tracker-App
```

Go to the frontend directory and Install dependencies

```bash
  cd client
```
```bash
  npm install
```

Go to the backend directory and Install dependencies

```bash
  cd server
```
```bash
  npm install
```

Start the frontend server

```bash
  npm start
```


Start the backend server

```bash
  npm run dev
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in backend folder

create config folder and add config.env file in it and all all env variables there.

`MONGO_URL` : Your MongoDB Connection String

`PORT`: PORT number

`JWT_SECRET` : Your Secret

`CLIPDROP_API` : Your API 

`RAZORPAY_KEY_ID` : Your Razorpay Key ID

`RAZORPAY_KEY_SECRET` : Your Razorpayment Key Secret

`CURRENCY` : "INR"














