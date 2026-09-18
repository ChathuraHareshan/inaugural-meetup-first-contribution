# 🧙‍♂️ JIAT FOSS Inaugural Meetup — First Contribution

[![JIAT FOSS Community](https://img.shields.io/badge/JIAT_FOSS-Community-FF6B35?style=for-the-badge&labelColor=1B2A47)](https://www.linkedin.com/company/jiat-foss-community/)
[![Open Sourcery](https://img.shields.io/badge/Open-Sourcery-4A6B36?style=for-the-badge&labelColor=1B2A47)](https://github.com/JIAT-FOSS-Community)

> **Your gateway to the open-source world starts here!** 🌍✨

This repository is the **live contribution project** for the JIAT FOSS Community's inaugural physical meetup on **September 19, 2026**. Every attendee will make their first open-source contribution by adding themselves to our participants page!

🔗 **[View the Live Participants Page](https://jiat-foss-community.github.io/inaugural-meetup-first-contribution/)**

---

## 🌿 What is This?

A beautiful, magically-themed web page that showcases every participant of the inaugural meetup. Each attendee contributes by:

1. **Forking** this repository
2. **Creating** a branch
3. **Adding** their details to a numbered JSON file
4. **Committing** and **pushing** their changes
5. **Opening** a Pull Request

This teaches the complete real-world open-source contribution workflow!

---

## 🗂️ Repository Structure

```
inaugural-meetup-first-contribution/
├── index.html                  # The main participants page
├── CONTRIBUTING.md             # Step-by-step contribution guide
├── README.md                   # You are here!
├── LICENSE.md                  # MIT License
├── participants/
│   ├── template.json           # Template — copy this!
│   ├── 001.json                # Participant #1 (Founder)
│   ├── 002.json                # Participant #2
│   └── ...                     # Your file goes here!
└── assets/
    └── images/
        ├── 001.jpg             # Participant #1 photo
        └── ...                 # Your photo goes here!
```

---

## 🚀 How to Contribute

👉 **[Read the full step-by-step guide →](CONTRIBUTING.md)**

**Quick version:**
```bash
# 1. Fork this repo on GitHub, then clone YOUR fork
git clone git@github.com:YOUR-USERNAME/inaugural-meetup-first-contribution.git
cd inaugural-meetup-first-contribution

# 2. Create a branch
git checkout -b add-participant-YOUR-NUMBER

# 3. Copy the template and fill in your details
cp participants/template.json participants/YOUR-NUMBER.json
# Edit the file with your name, branch, batch, github username

# 4. (Optional) Add your photo to assets/images/YOUR-NUMBER.jpg

# 5. Commit and push
git add .
git commit -m "feat: add participant YOUR-NUMBER - Your Name"
git push origin add-participant-YOUR-NUMBER

# 6. Open a Pull Request on GitHub!
```

---

## 📝 JSON Template

```json
{
  "number": 2,
  "name": "Your Full Name",
  "branch": "GAMPAHA",
  "batch": "YOUR BATCH",
  "image": "assets/images/002.jpg",
  "github": "your-github-username"
}
```

**Valid branches:** `GAMPAHA` | `COLOMBO` | `KANDY` | `KURUNEGALA` | `MATARA`

---

## 🤝 Community

- 💼 [LinkedIn](https://www.linkedin.com/company/jiat-foss-community/)
- 🐙 [GitHub Organization](https://github.com/JIAT-FOSS-Community)
- 📝 [Join the Community](https://tally.so/r/RGQ9L9)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE.md).

---

*Made with ❤️ by the JIAT FOSS Community — Open Sourcery since 2026*

#JIATFOSS #OpenSourcery #FOSS #OpenSource #FOSSLK #JavaInstitute #TechCommunity
