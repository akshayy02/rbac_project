# User Manual  

## Roles and Permissions  

### 1. Client Role  
- Log in to view and interact with assigned content.  
- Limited access to administrative tools.  

### 2. Admin Role  
- Manage users by adding, editing, or removing them.  
- Change user roles (Admin/Client) in the user management section.  

### 3. How to Use  
- Log in with your credentials.  
- Navigate to the "Users" section (Admin only) to manage or update user roles.  
- Clients can access their dashboard for content and features.  


The application is based on the **MVC pattern** i.e. Model View Controller.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.

---



## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/akshayy02/rbac_project
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```
Step 4: Start the app by

```bash
npm run dev
```

