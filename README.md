🧑‍💼 Fiverr Clone – Backend (MERN Stack)
A Node.js + Express backend for a Fiverr-like freelance marketplace, built using the MERN Stack.
This API powers user authentication, gig management, order processing, and other core marketplace functionalities — secured with JWT authentication and connected to MongoDB for persistent storage.

🚀 Features
🔐 JWT-based Authentication (Buyers & Sellers)

🎨 Create, edit, and delete gigs

🔍 Search and filter freelance services

📦 Order creation and tracking

👤 User profile management

🗄 MongoDB + Mongoose for data storage

⚙️ Configurable environment variables with dotenv

🛠 Tech Stack
Backend: Node.js, Express.js

Database: MongoDB + Mongoose

Authentication: JWT

Package Manager: Yarn / npm

📁 Folder Structure
fiverr-backend/
 ├── controllers/     # API request handlers
 ├── models/          # Mongoose schemas
 ├── routes/          # Express routes
 ├── middleware/      # Auth & error handling
 ├── utils/           # Helper functions
 ├── server.js        # App entry point
 └── .env.example     # Example environment variables
⚙️ Installation & Setup
1️⃣ Clone the Repository

git clone https://github.com/harshityadav1610/Fiverr-Backend.git
cd Fiverr-Backend
2️⃣ Install Dependencies

yarn install
3️⃣ Environment Variables
Create a .env file in the root folder:

env

MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
4️⃣ Run the Server
bash
Copy
Edit
yarn start
