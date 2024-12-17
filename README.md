# Sample Go/Web Server

A simple Go web server demonstrating basic HTTP routing, middleware, and graceful shutdown using Gorilla Mux and Logrus.

---

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/RafsanNeloy/go_Application.git
   ```  
3. **Install Dependencies**:  
   ```bash
   go mod tidy
   ```
4. **Start the Application**:  
   ```bash  
   go run main.go
   ```  

---

## ✨ Features  

- Simple HTTP server with two routes
- Structured logging with Logrus
- Middleware for request logging
- Panic recovery middleware
- Graceful server shutdown
- Environment variable-based port configuration

---

## 🛠️ Project Structure

- `main.go`: Primary application file with server logic
- `go.mod`: Go module dependency management

---

## 🔧 Dependencies

- [Gorilla Mux](https://github.com/gorilla/mux): HTTP request routing
- [Logrus](https://github.com/sirupsen/logrus): Structured logging

---

## 📡 Endpoints

- `GET /`: Returns a plain text "Hello, World!" message
- `GET /json`: Returns a JSON response

## 🌐 Configuration

Configure the server port using the `PORT` environment variable. Defaults to `8080` if not specified.
