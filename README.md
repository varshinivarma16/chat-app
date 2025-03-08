# Chat Application

## Objective  
The objective of this project is to develop a **real-time chat application** that allows users to communicate securely and efficiently. The application includes features such as:  
- **One-on-one messaging** and **group chats**  
- **Real-time updates** using WebSockets  
- **User authentication** and **profile management**  
- **Message encryption** for enhanced security  

The system is implemented using **MERN stack (MongoDB, Express, React, Node.js)** and **Socket.io** to enable seamless and instant communication.  

---

## Methodology  
The chat application follows a modular architecture with the following key components:  

### **Frontend (React.js)**  
- Responsive UI for smooth user experience  
- WebSockets integration for real-time messaging  

### **Backend (Node.js & Express.js)**  
- RESTful APIs for user authentication and message handling  
- WebSockets via **Socket.io** for real-time communication  

### **Database (MongoDB)**  
- Efficient storage of user profiles and chat history  
- Indexed queries for fast message retrieval  

### **Security Features**  
- **JWT-based authentication** for user security  
- **End-to-end encryption** to protect private messages  

---

## Contributions  
Key contributions of this project include:  
- **End-to-end chat application** with real-time messaging, authentication, and user management  
- **Optimized WebSocket handling** to reduce latency and ensure seamless chat experience  
- **Secure architecture** with user authentication, role management, and message encryption  

---

## Results  
The project achieved significant improvements in performance and scalability:  
- **Low latency messaging** with optimized WebSocket connections  
- **Scalability** to support multiple concurrent users  
- **Enhanced security** with authentication and encrypted message storage  

---

## Flowchart  
The system workflow includes:  
1. **User authentication** (Signup/Login using JWT)  
2. **WebSocket connection established** for real-time communication  
3. **Message transmission** (sent, received, stored in MongoDB)  
4. **Notifications** for new messages  
5. **Frontend updates dynamically**  

---

## How to Use This Repository  

### Prerequisites  
Ensure you have the following installed:  
- **Node.js** (v16 or later)  
- **MongoDB** (local or cloud-based, e.g., MongoDB Atlas)  
- **npm** or **yarn**  

### Installation Steps  

1. **Clone the repository** to your local machine:  
   ```sh
   git clone https://github.com/varshinivarma16/chat-app.git
   cd chat-app
   ```

2. **Install dependencies for the backend**  
   ```sh
   cd server
   npm install
   ```

3. **Install dependencies for the frontend**  
   ```sh
   cd ../client
   npm install
   ```

4. **Set up environment variables**  
   - Create a `.env` file in the **server** folder and add:  
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     ```

5. **Start the backend server**  
   ```sh
   cd ../server
   npm start
   ```

6. **Start the frontend server**  
   ```sh
   cd ../client
   npm start
   ```

7. **Access the application**  
   - Open your browser and go to:  
     ```sh
     http://localhost:3000
     ```
   - Sign up or log in to start chatting in real time.  

8. **Using the Application**  
   - **One-on-one Messaging**: Select a user and start a private conversation.  
   - **Group Chats**: Create or join groups for collaborative discussions.  
   - **Real-time Updates**: Messages update instantly via WebSockets.  
   - **User Authentication**: Secure login and profile management.  
   - **Message Encryption**: Ensures privacy and data protection.  

---
 
