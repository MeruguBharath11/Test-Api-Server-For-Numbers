# Test-Api-Server-For-Numbers
# Test Server APIs

This is a simple FastAPI project that provides a set of APIs to generate different types of number sequences such as prime numbers, Fibonacci numbers, even numbers, and random numbers.

## Features

- ✅ Generate the first `n` prime numbers
- ✅ Generate the first `n` Fibonacci numbers
- ✅ Generate the first `n` even numbers
- ✅ Generate `n` random numbers between 1 and 100

## Tech Stack

- [FastAPI](https://fastapi.tiangolo.com/) - for building the API
- [Uvicorn](https://www.uvicorn.org/) - for running the ASGI server

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install dependencies
Make sure you have Python 3.7+ installed.

bash
Copy
Edit
pip install -r requirements.txt
3. Run the server
bash
Copy
Edit
uvicorn main:app --reload
The server will start at http://127.0.0.1:8000.

API Endpoints
Endpoint	Description
/	Root route with welcome message
/primes	Returns a list of prime numbers
/fibonacci	Returns a list of Fibonacci numbers
/even	Returns a list of even numbers
/random	Returns a list of random numbers

All endpoints return 5 numbers by default. You can modify the code to accept a query parameter n if needed.

License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

You can save this as `README.md` in your project folder before pushing it to GitHub.

Would you like me to modify the code to accept a query parameter (e.g., `/primes?n=10`)?

