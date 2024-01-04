# FastCommerce

Welcome to the Fastcommerce Template! 🚀 This template provides a robust foundation for building e-commerce applications using [FastAPI](https://fastapi.tiangolo.com/), a modern and fast web framework for building APIs with Python 3.9+.

## Getting Started

### Prerequisites

- Python 3.9+
- Pip

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/NotThorz/Fastcommerce.git
    cd Fastcommerce
    ```

2. Create a virtual environment and install dependencies:

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```
3. Make sure you created the .env file using the .env.template as an example to connect the postgresSQL database

4. Run the FastAPI application:

      ```bash
      uvicorn app.main:app --reload
      ```

4. Access the APIs:

   - http://127.0.0.1:8000/docs

## API Endpoints

Explore the various API endpoints for managing users, products, and orders as outlined below:

### Users

- **Create User:** `POST /users/`
- **Get User:** `GET /users/{id}`
- **Update User:** `PUT /users/{id}`
- **Delete User:** `DELETE /users/{id}`

### Authentication

- **Login:** `POST /login`

### Products

- **Get Products:** `GET /products/`
- **Create Product:** `POST /products/`
- **Get Product:** `GET /products/{id}`
- **Update Product:** `PUT /products/{id}`
- **Delete Product:** `DELETE /products/{id}`
- **Mass Create Products:** `POST /products/mass-create`

### Orders

- **Get Orders:** `GET /orders/`
- **Create Order:** `POST /orders/`
- **Get Order:** `GET /orders/{id}`
- **Update Order:** `PUT /orders/{id}`
- **Delete Order:** `DELETE /orders/{id}`

### Default
- **Default route.**
## 
Feel free to customize and extend this template to meet the specific requirements of your e-commerce project. If you encounter any issues or have suggestions for improvements, please don't hesitate to open an issue or contribute to the repository.

Happy coding! 🚀
