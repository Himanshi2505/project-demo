#

This project is part of my MERN Stack From Scratch | eCommerce Platform course. It is a full-featured shopping cart with PayPal & credit/debit payments.(I was not able to complete credit /debit card features.)

This uses Redux Toolkit.

#Usage
Create a MongoDB database and obtain your MongoDB URI - MongoDB Atlas

#Env Variables
Rename the .env.example file to .env and add the following

NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'

#Install Dependencies (frontend & backend)
npm install
cd frontend
npm install

#Run

# Run frontend (:3000) & backend (:5000)

npm run dev

# Run backend only

npm run server

#Build & Deploy

# Create frontend prod build

cd frontend
npm run build

#Seed Database
You can use the following commands to seed the database with some sample users and products as well as destroy all data

# Import data

npm run data:import

# Destroy data

npm run data:destroy

Sample User Logins

admin@email.com (Admin)
123456

john@email.com (Customer)
123456

jane@email.com (Customer)
123456

#
