EarthBloom Perfume Catalogue – MERN Application
The EarthBloom Perfume Catalogue is a modern web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides a complete perfume browsing experience with product listing, search, sorting, cart management, and a mock checkout system. The design is clean, responsive, and user-friendly.

Features
Search perfumes by name, brand, or type
Sort products by price or alphabetically
Add items to cart, update quantity, and remove items
Checkout form with shipping and mock payment options
LocalStorage support for cart and orders
Fully responsive interface
Smooth and fast React-based UI

Tech Stack
Frontend
React.js
HTML, CSS
JavaScript

Backend
Node.js
Express.js
MongoDB / MongoDB Atlas

Project Structure
earthbloom-mern/
│── client/        → React Frontend  
│── server/        → Node + Express Backend  
│── package.json
│── README.md

How to Run the Project
1. Install Dependencies
Client:
cd client
npm install

Server:
cd server
npm install

2. Start the Backend
npm start

(Default: http://localhost:5000
)

3. Start the Frontend
npm run dev

(Default: http://localhost:5173
)

API Endpoints (Backend)
Method	Endpoint	Description
GET	/api/products	Fetch all perfumes
POST	/api/orders	Create new order
GET	/api/orders	View saved orders
Current Limitations
No real payment integration
Static product list (can be moved to database)
No admin dashboard
Future Enhancements
User authentication (login/register)
Admin product management
Cloud image hosting
Real online payment integration

Wishlist and user profiles
