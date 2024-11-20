# TodoApp | Full-Stack Task Management System  

A comprehensive task management system consisting of a **.NET 6 Minimal API (Server)** and a **React-based frontend (Client)**. The project integrates a seamless backend and frontend workflow to create, manage, and track tasks efficiently.  

---

## **Server: TodoAPI**  
The backend is built using **.NET 6 Minimal APIs** with **Entity Framework Core** for database interactions. The API handles task-related operations and provides dynamic RESTful endpoints for efficient communication with the frontend.  

### **Key Features**  
1. **CRUD Operations**  
   - Supports the creation, retrieval, updating, and deletion of to-do items.  
2. **Database Integration**  
   - Uses MySQL and Entity Framework Core for schema management and query execution.  
3. **CORS Configuration**  
   - Enables cross-origin requests to support frontend communication.  
4. **Swagger Documentation**  
   - Interactive API documentation for easy testing of endpoints.  
5. **Efficient Data Management**  
   - Includes triggers, procedures, and well-structured models for robust task handling.  

### **Endpoints Overview**  
- `GET /todoitems`  
  Retrieve all tasks.  
- `GET /todoitems/{id}`  
  Retrieve a task by its ID.  
- `POST /todoitems/{todo}`  
  Create a new task by name.  
- `PUT /todoitems/{id}/{isComplete}`  
  Update task completion status.  
- `DELETE /todoitems/{id}`  
  Delete a task by ID.  

---

## **Client: TodoApp Frontend**  
The frontend is a dynamic React-based web application that communicates with the backend API to provide a user-friendly interface for managing tasks.  

### **Key Features**  
1. **User-Friendly Interface**  
   - Intuitive design for task creation, editing, and deletion.  
2. **Real-Time Updates**  
   - Tasks are fetched and updated dynamically from the backend.  
3. **Responsive Design**  
   - Compatible with both desktop and mobile devices.  
4. **API Integration**  
   - Utilizes RESTful endpoints provided by the server for seamless data synchronization.  

### **Core Pages**  
- **Task List**  
  Displays all tasks retrieved from the server.  
- **Task Details**  
  Shows detailed information for a specific task.  
- **Task Management**  
  Allows users to create, edit, or delete tasks.  

