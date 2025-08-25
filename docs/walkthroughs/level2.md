# Walkthrough: Level 2 – Web Exploitation Basics  

Welcome to **Level 2** of the Allsafeafrica x SimulationsLab CTF challenge!  
In this stage, you’ll dive into **web exploitation** – one of the most common and fun areas of Capture The Flag.  

---

## 🎯 Challenge Goal  
You’re given a simple web application running at:  

http://example.com:8080


Your mission:  
- Explore the website.  
- Inspect the pages for hidden fields or weak security.  
- Find the **flag** hidden in the app.  

---

## 🛠️ Skills You’ll Practice  
- Using **browser developer tools** (Inspect, Console, Network tab).  
- Understanding **HTML forms** and hidden fields.  
- Spotting weak **client-side validation**.  
- Crafting and submitting **manipulated requests**.  

---

## 🕵🏾 Step-by-Step Hints  

1. **Look under the hood 🪛**  
   - Right-click → **Inspect** the page source.  
   - Search for hidden inputs (`<input type="hidden">`) or comments.  

2. **Check login forms 🔐**  
   - If there’s a login page, try looking at how it handles validation.  
   - Example: A JS snippet might be comparing your password in plaintext.  

3. **Play with request data 📨**  
   - Use browser dev tools or **Burp Suite Community Edition** (optional).  
   - Modify POST/GET requests to test if the server is really checking your input.  

4. **Common trick 💡**  
   - Sometimes the flag is directly in a comment:  
     ```html
     <!-- FLAG{client_side_fail} -->
     ```  

5. **Once you find it 🎉**  
   - Submit the flag in the platform:  
     ```
     FLAG{client_side_fail}
     ```  

---

## 📖 Why This Matters  
Web apps are everywhere – from banking systems to your favorite e-commerce site.  
If developers rely only on **client-side validation**, attackers can easily bypass it.  
That’s why real-world security requires **server-side checks** and **secure coding practices**.  

---

## ✅ Takeaway  
- Always check **both client and server-side security**.  
- Trust **but verify** inputs.  
- Beginners, professionals, and even enterprises must be aware of these risks.  

---

👩🏾‍💻 **Next Level:** SQL Injection 101 →  [Level 2](https://github.com/Allsafeafrica/Allsafeafrica-CTF/blob/main/docs/walkthroughs/level2.md) 
