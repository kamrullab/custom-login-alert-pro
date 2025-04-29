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
| ![settings](https://kamrul.us/img/settings.png) | ![alert](https://kamrul.us/img/alert.png) | ![history](https://kamrul.us/img/history.png) |

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
