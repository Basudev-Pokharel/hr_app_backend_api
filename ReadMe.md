# HR App Backend API

This is the **backend** for the HR Management App, built using **JSON Server** and deployed on **Render**.

## 🌐 API Base URL

`https://hr-app-backend-api-3gc8.onrender.com`

---

## 🌐 Live Demo

Backend API: [Render JSON Server](https://hr-app-backend-api-3gc8.onrender.com/employees)  
Frontend: [Load Frontend HR](https://react-hr-app-ashen.vercel.app/)

---

## 📂 Employees Endpoint

### 🔸 Base: `/employees`

#### 1. Get All Employees

```http
GET /employees
```

#### 2. Get a single Employee

```http
GET /employees/:id
```

#### 3. Add a new Employee

```http
POST /employees
Content-Type: application/json
Example Body:
{
  "name": "John Doe",
  "title": "Developer",
  "salary": "5000",
  "phone": "123456789",
  "email": "john@example.com",
  "animal": "lion",
  "startDate": "2025-01-01",
  "location": "Helsinki",
  "department": "IT",
  "skills": ["JavaScript", "React"]
}
```

#### 4. Update an existing Employee

```http
PUT /employees/:id
Content-Type: application/json
```

#### 4. Delete an Employee

```http
DELETE /employees/:id
```

---

✅ This version has **all endpoint instructions in one section** to make it faster and easier for your reference!
