# This application was developed for Web Application module, as coursework portfolio project @ WIUT by student ID: 00017186

## Calculation Process: 00017186 % 20 = 6 --> "Reception System App"

Table of Contents
-----------------

*   Overview
    
*   Prerequisites
    
*   Installation and Setup
    
    *   Client Setup
        
    *   Server Setup
        
*   Usage
    
*   Project Structure
    
*   Contributing
    
*   License
    

Overview
--------

This project is a web application that provides brief description of the functionality, e.g., payment processing or CRUD operations. It is built with **Angular** for the frontend and **ASP.NET Core** for the backend, with **MS SQL** as the database.

Prerequisites
-------------

Ensure you have the following installed on your system:

*   **Node.js** (version ≥ 18.19.0): [Download Node.js](https://nodejs.org/)
    
*   **npm** (comes with Node.js)
    
*   **.NET SDK** (for ASP.NET Core development): [Download .NET SDK](https://dotnet.microsoft.com/download)
    
*   **MS SQL Server** (for database management): [Download MS SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
    

Installation and Setup
----------------------

### Client Setup

1.  cd /client
    
2.  npm install
    
3.  node -v
    
4.  ng serve
    
5.  The frontend will be accessible at: [http://localhost:4200](http://localhost:4200)
    

### Server Setup

1.  cd /server/PaymentAPI
    
2.  dotnet restore
    
3.  "ConnectionStrings": { "DefaultConnection": "Your MS SQL connection string here"}
    
4.  dotnet ef database update
    
5.  dotnet run
    
6.  The backend will be accessible at its configured port (e.g., https://localhost:5001 or http://localhost:5000).
    

Usage
-----

1.  Start the frontend by running the ng serve command in the client folder.
    
2.  Start the backend by running the dotnet run command in the PaymentAPI folder.
    
3.  Open [http://localhost:4200](http://localhost:4200) in your web browser to interact with the application.