# Dashboards

**Dashboards** is a simple client-side role-based redirection system built using HTML and JavaScript. It simulates a login mechanism for two types of users: `admin` and `employee`. Based on the provided credentials, the user is redirected to their respective dashboard or an error page.

---

## 🌐 Features

- Simple JavaScript-based login
- Hardcoded username and password for:
  - `admin`
  - `employee`
- Role-based redirection to:
  - `admin.html`
  - `employee.html`
  - `blank.html` (for invalid users)

---

## 📁 File Structure

```
Dashboards/
│
├── index.html          # Main login page with authentication script
├── admin.html          # Admin dashboard
├── employee.html       # Employee dashboard
├── blank.html          # Fallback page for invalid credentials
└── (Optional assets like CSS/images if added)
```

---

## 🚀 How to Run the Project

> No installation required. This is a front-end-only project.

### Steps:

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/ananyaaa26/Dashboards.git
   ```

2. **Navigate to the project folder and open `index.html`**
   - You can double-click the `index.html` file.
   - Or run it in a local server (recommended for consistency):

     ```bash
     # Using Python 3 (if installed)
     python -m http.server

     # Then open in browser:
     http://localhost:8000/index.html
     ```

3. **Enter the credentials when prompted**

### Default Login Credentials:

| Username   | Password      | Role      |
|------------|---------------|-----------|
| admin      | admin1234     | Admin     |
| employee   | employee1234  | Employee  |
| *Any other*| *Any other*   | Invalid → redirected to `blank.html`

---

## ⚙️ Technologies Used

- HTML5
- Vanilla JavaScript

---

## 📌 Notes

- This project does **not** use a backend or real authentication. It’s only for demonstration purposes.
- All authentication logic is done client-side and should **not** be used in production environments.
