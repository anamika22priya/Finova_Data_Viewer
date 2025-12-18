# ARCHITECTURE REPORT 
## 1. CLIENT-SERVER MODEL
**Client:**
Device or software that initialises the communication to the server requesting data. 

**Server:**
It is a system that receives the client requests,processes them and returns the data/service.

**How they communicate?**

The client-server architecture works by:
1. The client sends the request.
2. The request is transferred through the network using the appropriate  protocol(eg.HTTP/HTTPS,FTP etc.)
3. The server receives the request,processes it and returns the required data/service.
4. The response is transferred through the network using the same protocol. 
5. The client receives the response. 

**What is supposed to happen when a user clicks Search in my UI?**

1. The client,i.e.,the web-application running in the user’s web browser, sends the query for the required stock/crypto information.
2. The query is transferred through the network using the HTTPS protocol.
3. The query is received by the server which holds all the stock/crypto information. 
4. The server processes the query.
5. The response from the server is transferred through the network using HTTPS. 
6. The response is received and processed by the client. 
7. The required stock or crypto data is displayed in the respective Stock or Crypto placeholder. 

## 2.FULL-STACK APPLICATIONS

**Frontend:**  
It is the component that the users interact with like the. It includes the UI and UX of the website. 

**Backend:**  
It is the server-side application logic that handles processing of data, managing application logic and handling user requests. It communicates with the database. 

**Database:**  
Stores and manages data required for the application. It can be SQL based databases(MySQL or PostgreSQL) or NoSQL based databases(MongoDB).

**API:**  
Application Programming Interfaces (APIs) are built on the backend server and serve as the interface between the frontend and backend. They define a set of endpoints and rules that control how client requests are processed, how the database is accessed and return structured responses. It is typically in JSON format. For web APIs, communication between the client and server usually occurs over HTTPS to ensure secure data transfer.

**How these layers talk to each other:**  
Frontend → API → Backend → Database → Backend → API → Frontend

## 3.DIAGRAM
![Flow of data in full-stack applications](/Finova_Data_Viewer/images/fullstack.png)

## 4.SCREENSHOTS


