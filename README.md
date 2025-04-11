# Echo Chat App

A simple and interactive **Java-based Echo Chat Application** that allows real-time text communication between client and server, with optional **database integration** to store chat messages.

---

## Features

- Real-time chat between client and server
- Socket programming using `java.net`
- JDBC-based **database integration** (e.g., MySQL)
- Simple and clean console-based UI
- Modular and easy-to-understand code

---

## Technologies Used

- **Java SE**
- **Socket Programming**
- **JDBC** for database connectivity
- **MySQL** (or any preferred RDBMS)

---

## How to Run

### 1. **Database Setup**
- Create a database (e.g., `chat_app`)
- Create a table to store messages:
```sql
CREATE TABLE messages (
    id INT AUTO_INCREMENT PRIMARY KEY,
    sender VARCHAR(50),
    message TEXT,
    timestamp DATETIME DEFAULT CURRENT_TIMESTAMP
);
```
- Update your `DBConnection.java` file with your DB credentials

---

### 2. **Compile the Code**
Open your terminal (or CMD) and navigate to the project folder:

```bash
javac *.java
```

---

### 3. **Run the Server**
Start the server first:
```bash
java Server
```

---

### 4. **Run the Client**
In another terminal window, run the client:
```bash
java Client
```

> You can run multiple clients to simulate multiple users.

---

## Folder Structure

```
EchoChatApp/
│
├── Server.java
├── Client.java
├── DBConnection.java
├── MessageHandler.java
├── README.md
```

---

## Screenshots

(Add screenshots here if you want to showcase how it works!)

---

## Author

- Your Name (Add your GitHub profile link here)

---

## License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).
