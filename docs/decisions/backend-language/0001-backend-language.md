# Backend Language

# Status

---

| Status | Approved   |
| ------ | ---------- |
| Date   | 2024-06-14 |

# Context

---

The backend needs to handle asynchronous operations efficiently and leverage a rich ecosystem of packages and libraries suitable for building the required functionalities of the app.

# Options considered

---

-   Node.js
-   Python (Django)
-   Java (Spring Boot)

# Decision

---

Option Chosen: **Node.js**

Node.js is highly efficient for handling asynchronous operations. Also, It have a vast ecosystem of packages and libraries that fits to the requirements of the application under consideration.

# Consequences

---

**Positive:**

Node.js handles asynchronous operations well and has a vast ecosystem of packages and libraries, which speeds up development.

**Negative:**

Managing callback hell and ensuring proper error handling can be challenging in a large-scale Node.js application.
