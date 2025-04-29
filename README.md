# 🔐 Custom Login Alert Pro

Real-time login alert system for WordPress with support for **Email**, **WhatsApp**, and **Facebook Messenger**.  
Includes **country detection with flag emoji**, **device info**, **dashboard login history**, and **Bangla + English auto language switching**.

---

## 🚀 Features

- ✅ Login alert on **Success & Failed** attempts  
- ✉️ **Email**, 📱 **WhatsApp**, 💬 **Messenger** notifications  
- 🌐 IP-based **Country Detection** (with flag emoji)  
- 🧠 Smart **Custom Message Template**  
- 📋 Built-in **Dashboard Login History**  
- 🌍 Supports **Bangla 🇧🇩** and **English 🇺🇸** (auto detect from WordPress site language)  
- ⚙️ No config required — Just install and go!

---

## 📸 Screenshot Preview

| Admin Settings Panel | Login Alert Example | Dashboard History |
|----------------------|---------------------|-------------------|
| ![wp-admin-admin-php-2025-04-29-20_42_28](https://github.com/user-attachments/assets/a4cc117f-4b45-4044-9cd4-6896d4ba503d)| ![Untitled](https://github.com/user-attachments/assets/f0dec826-bdb0-48c8-a984-420ad3e49b35)| ![wp-admin-2025-04-29-20_43_06](https://github.com/user-attachments/assets/3679c3a9-9489-4e24-9b9d-86c330f510c1)|

---

## 📦 Installation

1. Download or clone this repository.  
2. Upload to your `/wp-content/plugins/` directory.  
3. Activate via WordPress Admin > Plugins.  
4. Go to **Dashboard → Login Alert** to configure.

---

## 🧩 Message Template

Customize your message with the following variables:

```
{username}, {email}, {ip}, {country}, {browser}, {time}
```

### Example (auto multilingual):

```text
🔐 New login details:

👤 Name: {username}.  
📧 Email: {email}.  
🌐 IP: {ip}.  
🏳️ Country: {country}.  
💻 Device/Browser: {browser}.  
⏰ Time: {time}.
```

Or in Bangla (automatically):

```text
🔐 নতুন লগইন ডিটেলস:

👤 নাম: {username}.  
📧 ইমেইল: {email}.  
🌐 আইপি: {ip}.  
🏳️ দেশ: {country}.  
💻 ডিভাইস/ব্রাউজার: {browser}.  
⏰ সময়: {time}.
```

---

## 📞 WhatsApp & Messenger API

This plugin uses [CallMeBot](https://www.callmebot.com/) API  
✅ Free for personal use  
✅ No server needed  
✅ Easy setup with token

---

## 🌐 Multilingual Support

- Automatically detects WordPress language setting.  
- Sends login messages in **Bangla** or **English** accordingly.  
- Admin panel labels and UI are also translation-ready.

---

## 👨‍💻 Developer Info

**Author:** [Kamrul Hossain](https://kamrul.us)  
**GitHub:** [@kamrullab](https://github.com/kamrullab)  
**Facebook:** [elitekamrul](https://facebook.com/elitekamrul)

---

## 📄 License

This plugin is licensed under the GPL v2 or later.  
See [LICENSE](https://www.gnu.org/licenses/gpl-2.0.html) for full terms.
