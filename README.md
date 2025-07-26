🛒 eCommerce Platform Project – MERN Stack
Welcome to the eCommerce Platform — a full-featured online shopping solution built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). This project is designed to demonstrate real-world eCommerce functionalities including admin controls, user management, order processing, and a complete shopping experience.

⚠️ Note: The application is hosted on Render’s free tier, which may result in a few seconds delay on the first request after 15 minutes of inactivity. Subsequent requests will be faster.

🚀 Live Demo
Live Application Link (Replace with actual link when available)

🔑 Sample User Logins
🧑‍💼 Admin
Email: admin@admin.com

Password: admin123

👨‍💻 Customer Accounts
John Doe

Email: john@email.com

Password: john123

Alice Smith

Email: alice@email.com

Password: alice123

✨ Key Features
🛍️ User Side
Full Shopping Cart: Add, update, and remove products with dynamic totals.

Product Search: Keyword-based search functionality.

Product Pagination: Load products efficiently across multiple pages.

Product Reviews & Ratings: Leave feedback and rate items.

Top Products Carousel: Showcase featured or top-rated products.

User Profiles: View and update user information, see order history.

Checkout Flow:

Shipping Address

Payment Method (Razorpay – Coming Soon)

Place Order

🔐 Authentication
JWT-based Auth for secure login and session handling.

Protected Routes for authenticated users and admins.

🧑‍💻 Admin Dashboard
Admin Management: Add/update/remove admin accounts.

User Management: View all users, delete users.

Product Management: Create, edit, or delete products.

Order Management:

View order details.

Mark orders as delivered.

💳 Razorpay Integration (Coming Soon)
Secure payment integration using Razorpay is planned. Once implemented, users will be able to complete transactions directly through Razorpay’s gateway.

🛠️ Installation & Setup
Clone the repo and install dependencies:

bash
Copy
Edit
# Backend
npm install

# Frontend
cd frontend
npm install
▶️ Running the Application
Run both backend and frontend concurrently (uses concurrently package):

bash
Copy
Edit
npm run dev
To run only the backend API:

bash
Copy
Edit
npm run server
🔨 Build for Production
To create a production-ready React build:

bash
Copy
Edit
cd frontend
npm run build
This will generate static assets inside the /frontend/build folder ready for deployment.

🧪 Database Seeding
Use the following commands to manage initial data:

bash
Copy
Edit
# Import sample data (users + products)
npm run data:import

# Destroy all data in database
npm run data:destroy
Ensure MongoDB is connected before seeding.

🧰 Tech Stack
Frontend: React, React Router, Axios, Redux Toolkit, Bootstrap

Backend: Node.js, Express.js, MongoDB, Mongoose, JSON Web Tokens (JWT)

Deployment (Optional): Render / Vercel / Netlify / Railway

Payments (Planned): Razorpay

📌 Future Enhancements
 Razorpay Payment Integration

 Product Filtering (by price, category)

 Wishlist Feature

 Email Notifications

 Mobile App Version

