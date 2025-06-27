# E-commerce Project Overview
This project is a fully functional E-commerce website with AI-powered sales chatbot designed to simulate a virtual shopping assistant integrated into an e-commerce platform. The chatbot enables users to search, explore, and simulate the purchase of products through natural language conversations. It uses a RESTful API backend and a mock product inventory stored in an SQLite database.


Features
- Interactive chatbot interface with real-time messaging
- Smart product search using fuzzy matching
- Cart management (add to cart, clear cart)
- Checkout summary and total price calculation
- Mock e-commerce inventory with 100+ sample items
- RESTful API for product and cart management
- User authentication system (sign up, login, logout)

## Tech Stack
- Frontend: HTML5, CSS3, JavaScript
- Backend: Python (Flask framework)
- Database: SQLite (relational database for products and users)
- APIs: RESTful design for product search and cart handling



## Project Structure
```
├── app.py                  # Main Flask application
├── templates/
|   ├──index.html           #Shop page
│   ├── chat.html           # Chatbot interface
│   ├── home.html           # Home page
│   ├── login.html          # Login page
│   ├── sign-up.html        # Signup page
├── static/                 # Static assets (CSS, JS, images)
├── users.db                # User database
├── products.db             # Product database
├── README.md               # Project documentation
```

## Usage
- Visit `/signup` to create a new user account
- Log in via `/login`
- Access the chatbot interface at `/chat`
- Enter search queries like:
  - how me red shoes
  -Do you have black trousers?
  -Add white shirt to my cart
  - Checkout

## Sample Queries

"Show me black shoes" | Lists matching products |
"Add blue shirt to cart" | Adds the item to cart |
"Clear my cart" | Empties the cart |
"Checkout" | Shows cart summary and total |

Challenges Faced
- Ensuring fuzzy matching returned relevant product results
- Managing session-based cart storage without user-specific databases
- Handling dynamic UI responses in the chatbot using only JavaScript


Nathan Jiya 

