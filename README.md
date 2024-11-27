# Role-Based Access Control (RBAC) UI

## **Project Overview**

This project implements a **Role-Based Access Control (RBAC)** User Interface for managing users, roles, and permissions. It allows administrators to efficiently assign roles, define permissions, and manage user access in a secure and intuitive dashboard. The application is designed to provide a seamless and responsive experience, ensuring ease of use across devices.

## **Features**

### **Core Functionalities**
1. **User Management**
   - View, add, edit, and delete users.
   - Assign roles to users and manage their status (Active/Inactive).
2. **Role Management**
   - Create and edit roles.
   - Assign permissions (Read, Write, Delete) to roles.
   - Define custom attributes for roles.
3. **Dynamic Permissions**
   - Assign or modify permissions for roles dynamically.
   - Clearly display permissions for easier management.
4. **Custom API Simulation** (Optional)
   - Mock API calls to simulate CRUD operations for users and roles.
   - Validate functionality with simulated server responses.

### **Additional Features**
- **Search, Sort, and Filter**: Easily find users or roles with integrated search and filter options.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **Security Practices**: Input validation, error handling, and adherence to best practices for a robust user experience.

---

## **Tech Stack**

- **Frontend Framework**: React.js (or your chosen framework/library)
- **State Management**: Redux (or Context API, if applicable)
- **Styling**: Tailwind CSS / Bootstrap / Material-UI
- **API Simulation**: JSON Server / Axios (optional for mock API)

---

## **Setup Instructions**

### **Prerequisites**
- Node.js (v16+ recommended)
- npm or yarn package manager
- Git (for cloning the repository)

### **Installation**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/rbac-ui.git
   cd rbac-ui


---

## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/trulymittal/role-based-access-control
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

Step 4: Install MongoDB (Linux Ubuntu)

See <https://docs.mongodb.com/manual/installation/> for more infos

Step 5: Run Mongo daemon

```bash
sudo service mongod start
```

Step 6: Start the app by

```bash
npm start
```

## Author

- [**Resham Mahant**]

## Contribute

You can fork this repo and send me a PR.

## License

This project is licensed under the MIT License.
