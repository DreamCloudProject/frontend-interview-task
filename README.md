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
      "notes":"Top client",
      "activity":"Last contacted 2 days ago"
   },
   {
      "id":2,
      "name":"Jane Smith",
      "company":"Beta Corp",
      "email":"jane@beta.com",
      "status":"inactive",
      "notes":"Waiting for response",
      "activity":"Last contacted 1 week ago"
   },
   {
      "id":3,
      "name":"Alice Johnson",
      "company":"Gamma LLC",
      "email":"alice@gamma.com",
      "status":"active",
      "notes":"Met at conference",
      "activity":"Last contacted yesterday"
   },
   {
      "id":4,
      "name":"Bob Lee",
      "company":"Delta Inc",
      "email":"bob@delta.com",
      "status":"inactive",
      "notes":"Requested callback",
      "activity":"No contact yet"
   },
   {
      "id":5,
      "name":"Carlos Ramirez",
      "company":"Epsilon Partners",
      "email":"carlos@epsilon.com",
      "status":"active",
      "notes":"Frequent buyer",
      "activity":"Last contacted 3 days ago"
   },
   {
      "id":6,
      "name":"Diana Prince",
      "company":"Zeta Group",
      "email":"diana@zeta.com",
      "status":"active",
      "notes":"Potential lead",
      "activity":"Last contacted today"
   },
   {
      "id":7,
      "name":"Evan Thompson",
      "company":"Eta Networks",
      "email":"evan@eta.com",
      "status":"inactive",
      "notes":"Cold lead",
      "activity":"Last contacted 2 months ago"
   },
   {
      "id":8,
      "name":"Fiona Green",
      "company":"Theta Solutions",
      "email":"fiona@theta.com",
      "status":"active",
      "notes":"Interested in demo",
      "activity":"Last contacted 5 days ago"
   },
   {
      "id":9,
      "name":"George Brown",
      "company":"Iota Systems",
      "email":"george@iota.com",
      "status":"inactive",
      "notes":"Meeting scheduled",
      "activity":"Scheduled for next week"
   },
   {
      "id":10,
      "name":"Hannah White",
      "company":"Kappa Enterprises",
      "email":"hannah@kappa.com",
      "status":"active",
      "notes":"Important partner",
      "activity":"Last contacted 4 days ago"
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