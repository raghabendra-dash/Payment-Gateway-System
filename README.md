## PhonePe-Payment-Integration

Welcome to the Node.js Express PhonePe Payment Gateway Integration System! This project demonstrates the seamless integration of the PhonePe payment gateway into a Node.js and Express application.

> Hosted-  [Click](https://phonepe-gateway-system.onrender.com/)

### Features

/pay API: Initiate payments and redirect users to the PhonePe payment flow.
/payment/validate/:merchantTransactionId API: Validate payment status using merchantTransactionId.

### UAT Testing Credentials

For testing purposes in the UAT environment, use the following credentials:

Card number: `4242424242424242`
Expiry month: `12`
Expiry year: `44`
CVV: `936`
OTP: `123456`

### How to Run

Clone the project:
`git clone https://github.com/raghabendra-dash/PhonePe-Gateway-System.git`

Install dependencies:
`npm install`

Run the app:
`npm run start`

Open in your browser:
`http://localhost:3002/pay?amount=300`

### Dependencies

- Node.js
- Express.js
- Axios
- Body Parser (for handling JSON and URL-encoded data)
- SHA 256 (generating hash password)
- uniqid (for unique transaction ID)




### API Endpoints
**/pay API**: Initiate payments.
Method: GET
Endpoint: /pay
Parameters: amount (query parameter)

**/payment/validate** API: Validate payment status.
Method: GET
Endpoint: /payment/validate/:merchantTransactionId

