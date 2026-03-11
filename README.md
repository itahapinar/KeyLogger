# 🛡️ KEYLOGGER

A **C# WinForms application** that demonstrates keyboard event tracking and automatic log delivery via email using SMTP.

This project was created for **educational purposes** to explore:

- 🧠 Windows API usage
- ⌨️ Global keyboard hooks
- 📄 Logging systems
- 📧 SMTP email sending
- 🔐 Secure credential handling with **Environment Variables**

---

# ✨ Features

✔ Global keyboard tracking  
✔ Log collection system  
✔ Email sending with SMTP  
✔ Secure credential storage with Environment Variables  
✔ WinForms interface  

---

# 🧰 Technologies Used

| Technology | Purpose |
|------------|--------|
| **C#** | Main programming language |
| **.NET WinForms** | Desktop interface |
| **Windows API (user32.dll)** | Keyboard hooks |
| **SMTP** | Sending logs via email |
| **Environment Variables** | Secure credential storage |

---

# 🔐 Why Environment Variables?

Hardcoding sensitive data like **email passwords** inside source code is dangerous.

❌ **Unsafe Example**

```csharp
client.Credentials = new NetworkCredential("mail@gmail.com", "password");
