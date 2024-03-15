
Checkout Experience Project Overview
Welcome to the Checkout Experience project by GROWW! In this task, you'll create a user-friendly checkout process focusing on the final three steps: Checkout Page, Payment Options Page, and Order Confirmation Page.

Project Pages:

![Screenshot 2024-03-15 112909](https://github.com/nikhil0235/Insta_Payment/assets/109364387/d4ac706a-a3c0-4a64-9863-386e5ff24f25)

Checkout Page

Dynamic Cart UI: Fetches data from API.
Order Summary: Displays cart items, quantities, shipping charges, and GST. Includes a "Go to Payment" button.
Static Shipping Address Card.
Transaction ID: Generates a random ID stored using Zustand state manager.
Payment Options Page

Payment Modes.

![Screenshot 2024-03-15 113022](https://github.com/nikhil0235/Insta_Payment/assets/109364387/eca13976-b46f-40df-a4e3-9b0bdb720bdc)



Order Confirmation Page

Random Order Status: Success, failure, or pending.
![Screenshot 2024-03-15 113116](https://github.com/nikhil0235/Insta_Payment/assets/109364387/3214efee-548a-4015-83e6-062e71b0af12)

![Screenshot 2024-03-15 113053](https://github.com/nikhil0235/Insta_Payment/assets/109364387/9e8022c6-0949-429a-9609-8dbc2b6297ae)

Order Summary and selected payment method.


![Screenshot 2024-03-15 113034](https://github.com/nikhil0235/Insta_Payment/assets/109364387/2690ab24-259d-4bb6-ab78-c46011c1e63e)

404 Page
![Screenshot 2024-03-15 112841](https://github.com/nikhil0235/Insta_Payment/assets/109364387/f3cb6a4e-9723-4aee-905e-63518a815953)

Additional Feature
Implemented random themes fetched from API.

![Screenshot 2024-03-15 114235](https://github.com/nikhil0235/Insta_Payment/assets/109364387/a766ad64-f6ef-453d-85af-47d650489f2c)

Mobile Views 

![WhatsApp Image 2024-03-15 at 11 33 18_a606e10e](https://github.com/nikhil0235/Insta_Payment/assets/109364387/8c53a12d-7fdc-4153-a57b-097b50e3a53e)
![WhatsApp Image 2024-03-15 at 11 33 19_46259069](https://github.com/nikhil0235/Insta_Payment/assets/109364387/43e9dc02-5b40-4348-9267-f3d96875c1a4)
![WhatsApp Image 2024-03-15 at 11 33 18_e4827831](https://github.com/nikhil0235/Insta_Payment/assets/109364387/3bd4d212-b154-4e29-a03c-f64fdbad0e1f)




Tech Stack
NextJS
Typescript
MUI (UI framework)
Zustand (State Management)
Axios (API fetching)
Handling Various Scenarios
Skeleton loader for cart loading and full-page loader during theme changes.
Handling failures in cart API or zero products.
Logic for generating transaction IDs.
Address minor issues for better user experience.
Responsive UI for mobile, desktop, and tablet.

Getting Started
To get started with this project, ensure you have Node.js installed on your machine. This project requires Node.js version greater than 18. If you haven't installed Node.js yet, you can download and install it from the official website.

If you prefer to manage multiple Node.js versions, you can use Node Version Manager (nvm) and switch to version 20 with the following command:

nvm use 20
Next, clone this project repository from GitHub:

git clone https://github.com/nikhil0235/Insta_Payment.git
Navigate to the project directory:

cd Insta_Payment
Install project dependencies:

npm install
Start the development server:


npm run dev
Once the server is running, you can access the application at https://localhost:3000.
