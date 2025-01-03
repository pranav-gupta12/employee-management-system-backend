
# Employee Management System 🚀

Welcome to the **Employee Management System**, a full-stack web application for managing employee records seamlessly. Built using modern technologies, this project allows you to add, update, and delete employees while maintaining a clean and user-friendly interface.

---

## 🌟 Features
- **Create Employees**: Add a new employee by entering their first name, last name, and unique email address.
- **Update Employee Details**: Modify existing employee records with ease.
- **Delete Employees**: Remove employee records from the system.
- **Validation**: Ensures no two employees can have the same email ID.
- **Responsive Design**: Designed with Bootstrap for a clean and mobile-friendly UI.

---

## 🛠️ Tech Stack
### **Frontend**
- **ReactJS**: For building an interactive user interface.
- **Bootstrap**: For designing a responsive and visually appealing UI.
- **Axios**: For making API calls to the backend.

### **Backend**
- **Spring Boot**: To handle RESTful API services.
- **Lombok**: To simplify boilerplate code in Java.
- **MySQL (via Aiven)**: For storing employee data securely.

### **Hosting**
- **Frontend**: Hosted on [Vercel](https://ems-flame-sigma.vercel.app/).
- **Backend**: Hosted on Render with Docker.
- **Database**: Managed using Aiven's MySQL.

---

## 🌐 Live Demo
- **Frontend**: [Employee Management System](https://ems-flame-sigma.vercel.app/)
- **Backend API**: Hosted on Render.

---

## 📚 How to Use
1. Visit the [Frontend URL](https://ems-flame-sigma.vercel.app/).
2. Use the intuitive interface to:
   - **Add** a new employee by providing their first name, last name, and email.
   - **Update** an existing employee's details.
   - **Delete** an employee record.
3. Enjoy the smooth experience with instant feedback and validation.

---

## 🚀 Local Setup Instructions

### Prerequisites
- **Node.js** and **npm** (for the frontend)
- **Java JDK 17+** (for the backend)
- **MySQL** database (if running locally)

### Frontend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-management-system.git
   cd employee-management-system/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open the app at `http://localhost:5173`.

### Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd employee-management-system/backend
   ```
2. Update the `application.properties` file with your database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your_database
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```
3. Build and run the backend:
   ```bash
   mvn spring-boot:run
   ```
4. Backend will be live at `http://localhost:8080`.

---

## 🎨 Screenshots
### Home Page
![image](https://github.com/user-attachments/assets/47e4fd78-bb5f-4f76-84b5-245c1b0f9c67)


### Add Employee
![Add Employee]![image](https://github.com/user-attachments/assets/87f2d96b-0b6b-412c-930e-6eb2d131ed16)


---

## 📜 API Endpoints
Here’s a quick overview of the backend API endpoints:

| HTTP Method | Endpoint               | Description              |
|-------------|------------------------|--------------------------|
| `GET`       | `/employees`           | Fetch all employees      |
| `POST`      | `/employees`           | Add a new employee       |
| `PUT`       | `/employees/{id}`      | Update an employee       |
| `DELETE`    | `/employees/{id}`      | Delete an employee       |

Tested using **Postman** for smooth and error-free API interactions.

---

## 💡 Acknowledgements
Special thanks to:
- **Vercel** for hosting the frontend.
- **Render** and **Aiven** for managing the backend and database.
- The creators of **ReactJS**, **Spring Boot**, and **Bootstrap** for the awesome tools.

---

## 📬 Contact
For queries or suggestions, feel free to reach out:
- **GitHub**: https://github.com/pranav-gupta12
- **Email**: 12guptayash@gmail.com

## Frontend repo : 
- https://github.com/pranav-gupta12/ems-frontend
