# 🧪 Frontend Developer Interview Task

## 🚀 Task Overview

Build a simplified CRM dashboard with a client list, detail view, and ability to add or edit clients.

### 🎯 Core Features

- Client list with name, company, email.
- View client details: recent activity, notes, status.
- Edit client email and status.
- Add new client form with validation.

## 📐 Design Reference

Use the following Figma design as a visual reference for layout and UI components:

🔗 [CRM Dashboard Template](https://www.figma.com/design/RdzFjyRJAFlgnUkwzE0ffx/CRM-Dashboard?node-id=0-1&t=hoB1VJhYHLi87SBZ-1)

### 🪪 Mock Data

```
[
   {
      "id":1,
      "name":"John Doe",
      "company":"Acme Inc",
      "email":"john@acme.com",
      "status":"active",
      "salary":"$95,000",
      "startDate":"2023-03-15"
   },
   {
      "id":2,
      "name":"Jane Smith",
      "company":"Beta Corp",
      "email":"jane@beta.com",
      "status":"inactive",
      "salary":"$88,000",
      "startDate":"2022-11-01"
   },
   {
      "id":3,
      "name":"Alice Johnson",
      "company":"Gamma LLC",
      "email":"alice@gamma.com",
      "status":"active",
      "salary":"$105,000",
      "startDate":"2024-01-10"
   },
   {
      "id":4,
      "name":"Bob Lee",
      "company":"Delta Inc",
      "email":"bob@delta.com",
      "status":"inactive",
      "salary":"$79,500",
      "startDate":"2021-07-22"
   },
   {
      "id":5,
      "name":"Carlos Ramirez",
      "company":"Epsilon Partners",
      "email":"carlos@epsilon.com",
      "status":"active",
      "salary":"$92,300",
      "startDate":"2022-09-05"
   },
   {
      "id":6,
      "name":"Diana Prince",
      "company":"Zeta Group",
      "email":"diana@zeta.com",
      "status":"active",
      "salary":"$110,000",
      "startDate":"2023-06-01"
   },
   {
      "id":7,
      "name":"Evan Thompson",
      "company":"Eta Networks",
      "email":"evan@eta.com",
      "status":"inactive",
      "salary":"$76,000",
      "startDate":"2020-12-12"
   },
   {
      "id":8,
      "name":"Fiona Green",
      "company":"Theta Solutions",
      "email":"fiona@theta.com",
      "status":"active",
      "salary":"$98,750",
      "startDate":"2023-04-18"
   },
   {
      "id":9,
      "name":"George Brown",
      "company":"Iota Systems",
      "email":"george@iota.com",
      "status":"inactive",
      "salary":"$84,900",
      "startDate":"2023-10-09"
   },
   {
      "id":10,
      "name":"Hannah White",
      "company":"Kappa Enterprises",
      "email":"hannah@kappa.com",
      "status":"active",
      "salary":"$101,200",
      "startDate":"2024-02-28"
   }
]
```

### 💎 Bonus (Optional)

- Search and sort clients.
- Responsive layout (mobile/tablet).
- Persist data in `localStorage` or use a mock API.
- Include basic tests (unit/component).

---

## 🧰 Tech Stack

Feel free to use your preferred frontend stack. Recommended:
- React (or Vue / Angular / Svelte)
- TypeScript (preferred)
- TailwindCSS, SCSS, or any modern CSS-in-JS
- Optional: React Query / Zustand / Redux / Formik

---

## 🛠 Installation

```bash
# Clone the repo
git clone https://github.com/DreamCloudProject/frontend-interview-task.git
````