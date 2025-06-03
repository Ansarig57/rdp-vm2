# 🔐 Free RDP via GitHub Actions + Netlify

This project gives free RDP access using GitHub Actions. It auto-generates a password every 6 hours, and shows that password on a hosted webpage via Netlify.

---

## 📂 How it works:

- **GitHub Action** runs every 6 hours (cron job)
- It installs and runs **Playit Agent**
- It sets a new random RDP password for the user
- Password is saved in `rdp-password.txt`
- A public HTML page (`index.html`) shows this password live
- Hosted using **Netlify**

---

## 🔗 Links

- 🔓 [Live Website](https://your-netlify-link.netlify.app/)
- 📁 [Password File](rdp-password.txt)
- 📦 [Workflow File](.github/workflows/main.yml)
- ▶️ [YouTube Channel](https://www.youtube.com/@Sololeveling313)

---

## 🧠 Author

Made with ❤️ by [@Ansarig57](https://github.com/Ansarig57)
