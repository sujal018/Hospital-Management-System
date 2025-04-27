# Hospital-Management-System


# Hospital Management System

A full-stack **Hospital Management System** built with:
- 🧩 **Spring Boot** (Backend)
- 🎨 **Angular** (Frontend)
- 🛢️ **PostgreSQL** (Database)

This project manages hospital operations like patients, doctors, appointments, and administration with a clean, responsive web UI.

---

## 🛠️ Technologies Used

| Layer         | Technology         |
| -------------- | ------------------ |
| Backend        | Java, Spring Boot   |
| Frontend       | Angular             |
| Database       | PostgreSQL          |
| Tools          | Maven, Node.js, NPM |
| Others         | Git, Postman (API testing) |

---

## 📁 Project Structure

```
Hospital-Management-System/
├── backend/        # Spring Boot Backend
│   ├── src/main/java/
│   ├── src/main/resources/
│   ├── pom.xml
│   └── (Application code, Controllers, Services, Repositories)
│
├── frontend/       # Angular Frontend
│   ├── src/
│   ├── angular.json
│   ├── package.json
│   └── (Components, Services, Models)
│
├── README.md       # Project Readme
└── (Other project files)
```

---

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Maven 3.8+
- Node.js 18+
- Angular CLI
- PostgreSQL installed and running

### Backend Setup (Spring Boot)
1. Open a terminal inside the `backend/` folder.
2. Configure Database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/hospitaldb
   spring.datasource.username=your_db_username
   spring.datasource.password=your_db_password
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
4. Spring Boot server will start on `http://localhost:8080`.

### Frontend Setup (Angular)
1. Open a terminal inside the `frontend/` folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run Angular project:
   ```bash
   ng serve
   ```
4. Frontend will be running at `http://localhost:4200`.

---

## 🔥 Features

- User Authentication (Admin, Doctor, Patient)
- Patient Registration and Management
- Doctor Management
- Appointment Scheduling
- Medical Records Management
- Responsive Angular Frontend
- RESTful API integration with Spring Boot
- PostgreSQL database management

---

## 🌐 API Endpoints Example

| HTTP Method | Endpoint               | Description                   |
| ----------- | ----------------------- | ------------------------------ |
| GET         | `/api/patients`          | Get all patients               |
| POST        | `/api/doctors`           | Add a new doctor               |
| PUT         | `/api/appointments/{id}` | Update appointment details     |
| DELETE      | `/api/patients/{id}`     | Delete patient by ID           |

---

## 🖼️ Screenshots
![image](https://github.com/user-attachments/assets/3f76a788-b557-4540-81dd-b424436166b9)
![image](https://github.com/user-attachments/assets/b6b65cc2-5b34-4da8-91f9-07f7156347d4)
![image](https://github.com/user-attachments/assets/82d52905-bf9e-4c4c-ac78-d6496f2d0458)



## 📢 Contributing

Pull requests are welcome.  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

# ✨ Thank you for visiting!
Happy Coding 🚀
