# Full Stack Developer - Coding Challenge

**Duration:** 24-36 hours  
**Submission:** Public GitHub repository

## Challenge: Driver Wallet System

### Objective

Build a **wallet system** where drivers can **top up**, **check balance**, and see whether they can accept ride requests based on their wallet balance.

---

## Requirements

### 1. Backend (Laravel API)

✅ **Wallet Top-up API**

- `POST /api/wallet/topup`
- Accepts **driver_id** and **amount**.
- Ensures that a **failed transaction does not update the balance** (use database transactions).

✅ **Minimum Balance Check**

- `GET /api/wallet/balance/{driver_id}`
- Returns the driver's **current balance** and a status:
  - `"status": "Can accept rides"` (if balance ≥ 50 Birr).
  - `"status": "Insufficient balance, please top up"` (if balance < 50 Birr).

✅ **Algorithm Task: Second Largest Number**

- Write a function in **PHP** or another programming language your're comfortable with, to **return the second largest number** in an array in **O(n) time complexity**.

---

### 2. Frontend (React, React Native, or Vue)

✅ **Simple UI for Wallet System**

- Form for **driver top-up** (calls `POST /api/wallet/topup`).
- Display **current balance** and **status** (calls `GET /api/wallet/balance/{driver_id}`).
- Status should indicate whether the driver can accept rides or needs to top up.

---

## Bonus (Optional)

- **Unit tests** for the API.
- **Use Docker** to simplify setup.
- **Styling and UX improvements**.

---

## Submission Guidelines

1. **Push your code** to a **public GitHub repository**.
2. Include a **README.md** with setup instructions.
3. Ensure **clean, structured code** with meaningful commit messages.

---

## Evaluation Criteria

✅ Code structure & best practices  
✅ API design & error handling  
✅ Frontend integration with API  
✅ Optimization & performance  
✅ Documentation & clarity  
✅ Git usage & commit history
