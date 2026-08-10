A full-stack web application inspired by Paytm. This project simulates a digital wallet system where users can securely sign up, maintain a wallet balance, search for other users, and seamlessly transfer virtual money.

✨ Features
🔐 Secure Authentication: JWT-based user signup and login functionality.
💰 Virtual Wallet: Automatic wallet creation with a mock starting balance upon registration.
👥 User Directory: Search for other registered users on the platform to send money.
💸 Peer-to-Peer Transactions: Transfer funds securely between user accounts with ACID properties (using database transactions).
📱 Responsive UI: Clean, modern, and friendly user interface.
🛡️ Protected Routes: Secure frontend routes and backend endpoints accessible only to authenticated users.
🛠️ Tech Stack
Frontend:

React.js
Tailwind CSS (for styling)
React Router DOM
Fetch (for API requests)
Backend:

Node.js
Express.js
JSON Web Tokens (JWT) for authentication
Zod (for input validation)
Database:

PostgreSQL
PostgreSQL ORM
📸 Screenshots
Login Page	Dashboard Page	Transaction Page	Profile Page	Update Page	SignUp Page
Login	Dashboard	Transaction	Profile	Update	SignUp
🚀 Getting Started
Follow these steps to set up the project locally on your machine.

Prerequisites
Make sure you have the following installed:

Node.js (v14 or higher)
PostgreSQL (ORM) (Local instance or NeonDB URI)
Git
1. Clone the repository
git clone [https://github.com/BLACKPANTHER11544/paytm.git](https://github.com/BLACKPANTHER11544/paytm.git)
cd paytm
