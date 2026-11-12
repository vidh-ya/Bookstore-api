📚 BookStore REST API
A RESTful API built using FastAPI and Pydantic for managing books. This project supports complete CRUD (Create, Read, Update, Delete) operations with automatic data validation and interactive API documentation.

🚀 Features
Create a new book
Retrieve all books
Retrieve a specific book by ID
Update existing book details
Delete a book
Pydantic validation
FastAPI Swagger UI documentation
RESTful API architecture
🛠️ Technologies Used
Python 3
FastAPI
Pydantic
Uvicorn
📂 Project Structure
BookStoreAPI/
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
⚙️ Installation
Clone the Repository
git clone https://github.com/your-username/bookstore-api.git
cd bookstore-api
Create Virtual Environment
python -m venv myenv
Activate Virtual Environment
Windows:

myenv\Scripts\activate
Linux/macOS:

source myenv/bin/activate
Install Dependencies
pip install fastapi uvicorn pydantic
Or

pip install -r requirements.txt
▶️ Running the Application
uvicorn main:app --reload
The server will start at:

http://127.0.0.1:8000
📖 API Documentation
Swagger UI:

http://127.0.0.1:8000/docs
ReDoc:

http://127.0.0.1:8000/redoc
📌 API Endpoints
Get All Books
GET /books
Create a Book
POST /books
Request Body:

{
  "id": 1,
  "title": "Python Programming",
  "author": "Guido van Rossum",
  "price": 499.99
}
Get Book by ID
GET /books/{book_id}
Example:

GET /books/1
Update Book
PUT /books/{book_id}
Request Body:

{
  "id": 1,
  "title": "Advanced Python",
  "author": "Guido van Rossum",
  "price": 799.99
}
Delete Book
DELETE /books/{book_id}
Example:

DELETE /books/1
✅ Sample Response
{
  "id": 1,
  "title": "Advanced Python",
  "author": "Guido van Rossum",
  "price": 799.99
}
🎯 Learning Outcomes
Through this project, the following concepts were learned:

FastAPI fundamentals
REST API development
CRUD operations
Pydantic validation
API documentation with Swagger
Python backend development
👩‍💻 Author
Vidhyasri

B.Tech Information Technology

