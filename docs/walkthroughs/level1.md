# Level 1 Walkthrough: Beginner Challenge 🎯

Welcome to **Level 1** of the Allsafeafrica x SimulationLabs CTF Challenge! 🚀  
This guide walks you through solving the very first challenge step by step. If you're new to Capture The Flag (CTF), this is the perfect starting point.

---

## 🔑 Challenge Description

**Title:** Hidden Message in Plain Sight  
**Category:** Web / Basic OSINT  
**Difficulty:** Beginner  

**Prompt:**
> We’ve hidden a secret message on a simple webpage. Can you find it?

**Goal:** Retrieve the hidden flag from the challenge website.

---

## 🛠 Tools You’ll Need
- Any **web browser** (Chrome, Firefox, Edge, etc.)
- **Right-click > View Page Source** feature
- (Optional) **Developer Tools** (F12)

---

## 📝 Step-by-Step Walkthrough

### Step 1: Visit the Challenge Page 🌍
Go to the provided challenge link (example: `http://ctf.allsafeafrica.com/level1`).  
The page might look super simple with a welcome message.

### Step 2: Inspect the Page 🕵️
Right-click anywhere on the page and select **View Page Source**.  
Alternatively, press `Ctrl+U` (Windows/Linux) or `Cmd+Option+U` (Mac).

### Step 3: Search for Hidden Clues 🔍
Scroll through the HTML code.  
Look for suspicious comments (anything inside `<!-- -->`).

Example:
```html
<!-- Congratulations! You found the flag: FLAG{hidden_in_source} -->
```

### Step 4: Capture the Flag 🚩
The flag will usually follow this format:
```
FLAG{something_secret_here}
```
Copy it and submit on the CTF platform to earn your first points 🎉

---

## ✅ Key Takeaways
- Always check **page source** – hidden comments often contain secrets.
- Flags usually follow a standard format like `FLAG{}`.
- CTFs teach you to **think beyond what’s visible**.

---

## 📌 Pro Tips for Beginners
- Don’t overthink early challenges – start simple.
- Learn to use browser developer tools effectively.
- Take notes of every step you try.

---

## 🎓 What You Learned
By completing this level, you practiced:
- Basic **OSINT & HTML inspection**
- Finding **hidden messages in source code**
- Submitting your first CTF flag 🚀

---

👨🏾‍💻 Next: Move on to [Level 2](../level2.md) where we explore deeper into **basic cryptography** 🔐.
