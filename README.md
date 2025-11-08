📁 Network File Sharing – Server & Client
🧠 Objective

Develop a C++-based networked file sharing application with a client-server architecture. The project enables users to transfer files over sockets, including downloading and uploading files securely.

📅 Day-wise Development Plan
Day 1 – Socket Communication Setup

Implemented TCP socket communication between server and client.

The server listens for incoming client connections.

Clients connect using the server’s IP and port.

Day 2 – File Listing & Selection

The server provides a list of available files.

The client displays this list and allows the user to select a file.

Day 3 – File Download

Implemented file transfer from server to client.

The server reads the requested file and sends data in chunks.

The client receives and saves the file locally.

Day 4 – File Upload

Added functionality for clients to upload files to the server.

The server receives the file data and stores it in a designated directory.

Day 5 – Security Enhancements

Added user authentication (username/password).

Implemented basic encryption for data transmission to ensure confidentiality.

⚙️ Technologies Used

Language: C++

Libraries: <sys/socket.h>, <arpa/inet.h>, <unistd.h>, <fstream>, <iostream>

Protocol: TCP/IP

🧩 How to Run

Compile the programs:

g++ server.cpp -o server
g++ client.cpp -o client


Run the server:

./server


Run the client (in another terminal):

./client


Follow on-screen prompts to connect, view files, and transfer data.

🔐 Features

✅ Client-server communication via sockets
✅ File listing, download, and upload
✅ Basic authentication system
✅ Simple encryption for secure transfer
✅ Modular, day-wise code structure

📚 Future Enhancements

Add GUI for better usability

Enable multiple concurrent clients

Implement advanced encryption (SSL/TLS)

Add file compression before transfer
