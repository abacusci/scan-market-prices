# QR Price

**A public tool to help vendors in Suriname display real-time product prices using QR codes.**

This project was created as a social and educational initiative by Abacus Computing Institute, Suriname. It allows markets to publish their product prices transparently, so customers can scan and verify the price, VAT, and other details instantly using their phones.

---

## 🎯 Purpose

- Improve price transparency in local markets
- Help vendors update and display prices without confusion
- Avoid the effects of dollar fluctuation on labeling
- Enable simple digital inclusion for small merchants
- Provide a real-world educational project for students

---

## 🛠 Features

- Anonymous product submission form
- Public product page via QR code
- Edit products using a private token (no login needed)
- Local browser dashboard (via LocalStorage)
- CAPTCHA protection for spam control
- QR codes can represent a single product or a group sharing the same USD reference
- Prices can be entered in SRD directly, or in USD with:
  - a manual conversion rate
  - or an automatic rate based on public exchange data from paramaribo.info
- PostgreSQL backend, PHP REST API, HTML/JS frontend
- Works 100% without frameworks or external services

---

## 🗺 Deployment

You can self-host this system or use the public instance at:

> https://qrprice.paramaribo.info

This platform is and will always be **free to use**.

---

## 👨‍💻 Tech Stack

- PHP (no Composer required)
- PostgreSQL
- HTML / JavaScript / CSS
- QR generation with phpqrcode
- CAPTCHA via native PHP/GD

---

## 📖 License

MIT License – see [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Feel free to fork or suggest improvements. This project is open source and community-driven. Help us improve access to information and promote transparency across Suriname and beyond.
