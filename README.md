# Backend Integration with Razorpay and Zoho CRM

This project implements a backend system that integrates payment handling through Razorpay and automates the creation of leads in Zoho CRM. The application accepts payments via Razorpay, captures payment details using a webhook, and stores the information as leads in Zoho CRM.

[Demo Video](https://drive.google.com/file/d/1FfERafT5x9WtyTcLJcOnfzEaPu_iD2he/view)

## Features

- Accepts payments using Razorpay's payment gateway.
- Captures payment details (amount, currency, payment ID, order ID, etc.).
- Automatically stores the payment information as a lead in Zoho CRM.
- Supports webhook integration for seamless data flow between Razorpay and Zoho CRM.

## Technologies Used

- **Python**: The primary language used to write the backend logic.
- **Flask**: A lightweight web framework for handling routes and views.
- **Razorpay API**: To process payments and handle transaction details.
- **Zoho CRM API**: To manage lead information and integrate with CRM.
- **Requests**: Python library to make HTTP requests to Zoho's API.
- **HTML, CSS, JavaScript**: Frontend technologies to handle form inputs and rendering.

## Installation and Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/repo-name.git
   cd repo-name
2. **Install Dependencies:**

   ```bash
   pip install Flask razorpay requests
3. **Set up Razorpay and Zoho CRM credentials:**

- You will need API keys from Razorpay for processing payments. Sign up at Razorpay to get your API keys.
- You'll also need to generate an access token from Zoho CRM. Check Zoho's API documentation for instructions on how to do that.
4. **Running the application:**
  
  After setting up your API credentials, run the app:
  ```bash
  python main.py

