# 📌 Frontend — `README.md`

```markdown
# ECommerceDb Frontend

This is the frontend for the **Full Stack E-commerce Assignment**, built with **Angular**.

## 🏗️ Project Structure

````

src/app/
├─ core/        # services, models, guards, interceptors
├─ features/
│    ├─ auth/       # login component
│    └─ products/   # product list component
├─ shared/      # shared UI components
└─ app.routes.ts

````

- **Auth** → Login form, token storage, API integration.
- **Products** → Product list display, fetching from backend.
- **Core** → Reusable services (auth service, product service).
- **Shared** → Common UI components.

## 🚀 Features

- **Login** with JWT authentication.
- **Product list** display.
- Angular **signals & RxJS** for state management.
- **HTTP Interceptor** for attaching JWT tokens.
- Clean, modular structure.

## 🛠️ Setup Instructions

1. Install dependencies:
   ```bash
   npm install
````

2. Update backend API URL in `environment.ts`:

   ```ts
   export const environment = {
     apiUrl: 'http://localhost:5000/api'
   };
   ```

3. Run the Angular app:

   ```bash
   ng serve
   ```

4. Navigate to:

   ```
   http://localhost:4200
   ```

## 👤 Test User Credentials

* **Username**: `testuser`
* **Password**: `P@ssw0rd123`

## ✅ Notes

* The login page requires a valid backend running.
* Product images are fetched from the backend (`http://localhost:5000/images/...`).
