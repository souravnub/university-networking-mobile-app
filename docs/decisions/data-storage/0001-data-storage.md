# Data Storage

# Status

---

| Status | Approved   |
| ------ | ---------- |
| Date   | 2024-06-14 |

# Context

---

We need a flexible, scalable database to handle varied and evolving data structures like user profiles, class schedules, and event details.

# Options considered

---

-   PostgreSQL
-   MongoDB
-   Firebase Firestore

# Decision

---

Option Chosen: **MongoDB**

MongoDB’s flexible schema is ideal for handling varied and evolving data structures like user profiles, class schedules, and details about events. It also supports horizontal scaling, which aligns with our scalability requirements.

# Consequences

---

**Positive:**

MongoDB’s flexible schema accommodates changes in data structure without requiring major changes to the database. It also supports horizontal scaling.

**Negative:**

Schema-less design might lead to data integrity issues, and complex transactions can be challenging to implement.
