# React + Django Full Stack CRUD Application

A comprehensive full-stack web application demonstrating how to build a CRUD (Create, Read, Update, Delete) system using **React** for the frontend and **Django** (with Django REST Framework) for the backend. This project is based on the [PedroTech YouTube tutorial](https://www.youtube.com/watch?v=xldTxXtNiuk), which guides you through setting up both frameworks, integrating them, and implementing full CRUD operations.

---

## 🚀 Features

- **Frontend:** Built with React (using Vite for fast setup and development)
- **Backend:** Django with Django REST Framework for API development
- **Database:** SQLite (default with Django, easily swappable)
- **CORS Handling:** Seamless communication between frontend and backend
- **CRUD Operations:** Add, view, update, and delete book records
- **RESTful API:** Clean separation of concerns and scalable structure

---

## 🛠️ Technologies & Skills Used

### **Frontend (React)**
- **React** (with Vite)
- **JavaScript (ES6+)**
- **React Hooks** (`useState`, `useEffect`)
- **Fetch API** for HTTP requests
- **Component-based architecture**
- **State management**
- **Form handling and input validation**

### **Backend (Django + Django REST Framework)**
- **Django** (Python web framework)
- **Django REST Framework (DRF)** for building RESTful APIs
- **Python 3**
- **Model-View-Serializer pattern**
- **Django Models** (defining database schema)
- **Django Serializers** (converting between model instances and JSON)
- **Django Views** (API endpoints for CRUD)
- **Django URL Routing**
- **Database migrations** (`makemigrations`, `migrate`)
- **CORS Headers** (`django-cors-headers` for cross-origin requests)

### **Integration & DevOps**
- **CORS Configuration** for safe cross-origin communication
- **Local development environment** (VSCode, terminal, etc.)
- **API Testing** (using browser/Postman)
- **Error handling and status codes** (201 Created, 400 Bad Request, 404 Not Found, etc.)

---

## 📦 Project Structure


---

## 📚 How It Works

1. **Frontend** (React)
    - Displays a list of books fetched from the Django backend.
    - Provides forms to add new books and update existing ones.
    - Allows deletion of books.
    - Communicates with the backend via RESTful API endpoints.

2. **Backend** (Django + DRF)
    - Exposes API endpoints for:
        - Listing all books (`GET`)
        - Creating a book (`POST`)
        - Updating a book (`PUT`)
        - Deleting a book (`DELETE`)
    - Handles database operations and data validation.
    - Uses serializers to convert between Python objects and JSON.

3. **Integration**
    - CORS is enabled to allow the React frontend to interact with the Django backend.
    - API endpoints are organized and routed for easy access and scalability.

---

## 📝 Setup Instructions

### **Backend (Django)**
1. Clone the repo and navigate to `server/`
2. Install dependencies:
    ```
    pip install django djangorestframework django-cors-headers
    ```
3. Run migrations:
    ```
    python manage.py makemigrations
    python manage.py migrate
    ```
4. Start the server:
    ```
    python manage.py runserver
    ```

### **Frontend (React)**
1. Navigate to `client/`
2. Install dependencies:
    ```
    yarn install
    ```
3. Start the development server:
    ```
    yarn dev
    ```

---

## 🌐 API Endpoints

- `GET /api/books/` - List all books
- `POST /api/books/create/` - Create a new book
- `PUT /api/books/<id>/` - Update a book by ID
- `DELETE /api/books/<id>/` - Delete a book by ID

---

## 🧑‍💻 Author & Credits

- Tutorial by [PedroTech](https://www.youtube.com/@pedrotech)
- Codebase: [machadop1407/react-django-tutorial](https://github.com/machadop1407/react-django-tutorial)

---

## 📣 Contributing

Feel free to fork this repository and submit pull requests for improvements or bug fixes!

---

## 📜 License

This project is for educational purposes. Refer to the original tutorial and repository for licensing details.
