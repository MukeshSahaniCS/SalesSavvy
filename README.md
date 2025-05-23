🛒 SalesSavvy
SalesSavvy is a modern e-commerce solution designed for small and medium businesses.
It provides a complete platform for product management, secure transactions, and smooth customer experience.

🚀 Features
Admin Panel: Manage products, categories, users, and orders.

Customer Interface: Browse products, add to cart, place orders, and track order status.

Authentication: Secure login and registration system (JWT-based).

Payments: Integrated with Razorpay for seamless payment processing.

Order Management: Real-time order tracking and status updates.

Responsive UI: Mobile-friendly and easy-to-use frontend (ReactJS).

Scalable Backend: Built with Java Spring Boot and MySQL database.

🛠️ Tech Stack
Frontend | Backend | Database | Payment Gateway
ReactJS | Spring Boot | MySQL | Razorpay
📂 Project Structure

SalesSavvy/
├── frontend/ (ReactJS Code)
└── backend/ (Spring Boot APIs)

⚙️ Setup Instructions

1. Clone the Repository

   git clone https://github.com/MukeshSahaniCS/SalesSavvy.git
   cd SalesSavvy

2. Setup Backend
   Go into backend/ folder.
   Configure database credentials in application.properties.
   Run the Spring Boot application.

3. Setup Frontend
   Go into frontend/ folder.
   Install dependencies:
   npm install
   Create a .env file and add:
   REACT_APP_RAZORPAY_KEY=your_razorpay_key_here
   Run the React app:\
   npm start

🔒 Environment Variables
You must configure the following environment variables:

      Variable          |       Description

REACT_APP_RAZORPAY_KEY | Razorpay Public Key for payments

🛑 Do NOT commit your .env file to GitHub. Always add .env in .gitignore.

📸 Screenshots (Coming Soon)
(You can later add Admin Panel and Customer UI screenshots here.)

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to submit a pull request.

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙋‍♂️ Author
Mukesh Sahani

[GitHub](https://github.com/MukeshSahaniCS/SalesSavvy/)

🔥 Happy Coding with SalesSavvy! 🔥
