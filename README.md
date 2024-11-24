# Role Based Access Control - VRV Security

This is my implementation of the Role Based Access Control assignment for VRV Security AI company. The application demonstrates a robust authentication and authorization system using Node.js, Express, and Passport JS technology stack.

Built as part of the technical assessment for VRV Security AI's authentication module requirements, this solution implements secure role-based access control that can serve as a foundation for enterprise-level security implementations.

For the current implementation, I've focused on Email & Password authentication, though the architecture supports easy integration of additional authentication methods via OAuth/OAuth2.0 (Google, Facebook, Apple, GitHub, etc.) as per future requirements.

The application follows the **MVC pattern** (Model View Controller) for clean code organization and maintainability.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.


---

## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/Vardaan31/VRV-RBAC.git
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3008
MONGODB_URI=mongodb+srv://vardaan20258:PI6DtIjPQ3XPW4c4@cluster0.vfopk.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
DB_NAME=rbac_tutorial
SESSION_SECRET=some super secret
ADMIN_EMAIL=admin@gmail.com
```
Step 4: Start the app by

```bash
npm start
```

Step 5: Login using ADMIN credentials.

```bash
email: admin@gmail.com
password: admin
```

## Author

- [**Vardaan Abrol**](https://vardaanabrol.vercel.app)

