<p align="center">
  <img src="https://envs.sh/5x8.jpg" width="100%" alt="Repo Banner" />
</p>

<h1 align="center">Gita Slokas Api</h1>

<p align="center">
  <a href="https://github.com/pykinsu/gita-slokas-api/stargazers" target="_blank">
    <img src="https://img.shields.io/github/stars/pykinsu/gita-slokas-api?style=for-the-badge&logo=github" alt="Stars Badge"/>
  </a>
  <a href="https://github.com/pykinsu/gita-slokas-api/network/members" target="_blank">
    <img src="https://img.shields.io/github/forks/pykinsu/gita-slokas-api?style=for-the-badge&logo=github" alt="Forks Badge"/>
  </a>
  <a href="https://github.com/pykinsu" target="_blank">
    <img src="https://img.shields.io/badge/Follow%20Me%20on-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Follow me on GitHub"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/FastAPI-Coming%20Soon-green?style=for-the-badge&logo=fastapi" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License"/>
</p>

## 📖 About

**Gita Slokas Api** provides easy access to all 700 verses of the Bhagavad Gita through a simple REST API. Each verse includes:

- 📜 **Original Sanskrit** text
- 🇮🇳 **Hindi translation** 
- 🇬🇧 **English translation**
- 💭 **Commentary** in both languages

Perfect for building spiritual apps, educational tools, or daily verse features.

---

## 🚀 Quick Start

Documentation & Usage Coming Soon 🙂

**Expected Launch:** Q2 2024

---

## 📊 Data Structure

Each verse follows this JSON format:

```json
{
  "id": 247,
  "chapter": 2,
  "verse": 47,
  "sanskrit": "कर्मण्येवाधिकारस्ते मा फलेषु कदाचन",
  "translation_hindi": "तुम्हारा अधिकार केवल कर्म में है, फल में कभी नहीं",
  "translation_english": "You have a right to perform your duty, but not to the fruits",
  "commentary_hindi": "इस श्लोक में निष्काम कर्म का सिद्धांत समझाया गया है",
  "commentary_english": "This verse teaches the principle of selfless action",
  "reference": "2.47"
}
```

---

## 📈 Development Roadmap & Progress

<div align="center">

### 🎯 **Overall Progress: 0/700 Verses**

![Progress Bar](https://img.shields.io/badge/📊_Complete-0%25-red?style=for-the-badge)
![Remaining](https://img.shields.io/badge/📋_Remaining-700_verses-orange?style=for-the-badge)

</div>

### Chapters Overview

| Chapter | Name | Verses | Status |
|---------|------|--------|--------|
| 1 | अर्जुनविषादयोग | 47 | 0 |
| 2 | सांख्ययोग | 72 | 0 |
| 3 | कर्मयोग | 43 | 0 |
| 4 | ज्ञानकर्मसंन्यासयोग | 42 | 0 |
| 5 | कर्मसंन्यासयोग | 29 | 0 |
| 6 | आत्मसंयमयोग | 47 | 0 |
| 7 | परमहंसयोग | 30 | 0 |
| 8 | अक्षरब्रह्मयोग | 28 | 0 |
| 9 | राजविद्याराजगुह्ययोग | 34 | 0 |
| 10 | विभूतियोग | 42 | 0 |
| 11 | विश्वरूपदर्शनयोग | 55 | 0 |
| 12 | भक्तियोग | 20 | 0 |
| 13 | क्षेत्रक्षेत्रज्ञविभागयोग | 35 | 0 |
| 14 | गुणत्रयविभागयोग | 27 | 0 |
| 15 | पुरुषोत्तमयोग | 20 | 0 |
| 16 | दैवासुरसम्पद्विभागयोग | 24 | 0 |
| 17 | श्रद्धात्रयविभागयोग | 28 | 0 |
| 18 | मोक्षसंन्यासयोग | 78 | 0 |

---

## 🗺️ Roadmap

### Phase 1: Data Collection ⏳ **(Sep 2025 - Oct 2025)**
- [ ] Collect and verify Sanskrit verses
- [ ] Add Hindi translations
- [ ] Add English translations  
- [ ] Include authentic commentaries

### Phase 2: API Development 🔧 **(Sep 2025 - Oct 2025)**
- [ ] Build REST API with Python FastAPI
- [ ] Add search functionality
- [ ] Create API documentation
- [ ] Add rate limiting

### Phase 3: Frontend 🖥️ **(Sep 2025 - Oct 2025)**
- [ ] Build reading interface
- [ ] Add chapter navigation
- [ ] Implement search feature
- [ ] Make mobile responsive

### Phase 4: Advanced Features ✨ **(Dec 2025+)**
- [ ] Daily verse feature
- [ ] Audio pronunciation
- [ ] User bookmarks
- [ ] Sharing capabilities

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Ways to Contribute
- ✅ **Add verses** with accurate translations
- ✅ **Improve API** functionality  
- ✅ **Fix bugs** and issues
- ✅ **Enhance documentation**
- ✅ **Test on different devices**

### Getting Started
1. **Fork** the repository
2. **Create** a new branch (`git checkout -b feature/chapter-1`)
3. **Make** your changes
4. **Test** your changes
5. **Submit** a pull request

### Guidelines
- Use authentic sources for translations
- Follow the existing JSON structure
- Test your changes before submitting
- Write clear commit messages

---

## 📄 Project Structure

```
gita-slokas-api/
├── data/
│   ├── gita_1.json
│   ├── gita_2.json
│   └── ... (18 chapters)
├── api/
│   └── (coming soon)
├── frontend/
│   └── (planned)
├── tests/
├── requirements.txt
└── README.md
```

---

## 📞 Support

<p>
  <a href="https://github.com/pykinsu" target="_blank">
    <img alt="GitHub" src="https://img.shields.io/badge/GitHub-%23000000.svg?&style=for-the-badge&logo=Github&logoColor=white" />
  </a>
  <a href="https://t.me/pykinsu" target="_blank">
    <img alt="Telegram" src="https://img.shields.io/badge/Telegram-%2326A5E4.svg?&style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/pykinsu" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://twitter.com/pykinsu" target="_blank">
    <img alt="Twitter" src="https://img.shields.io/badge/Twitter-%23000000.svg?&style=for-the-badge&logo=x&logoColor=white" />
  </a>
</p>

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Sacred texts and translations from authenticated sources
- Contributors and maintainers of this project
- The timeless wisdom of the Bhagavad Gita

---

<div align="center">

**⭐ Star this repo • 🔄 Share with friends • 🤝 Contribute today**

</div>

---

<div align="center">
<sub>💡 <i>This project combines reverence for ancient wisdom with modern development practices. Every line of code and every verse is handled with the utmost respect for the sacred nature of the Bhagavad Gita.</i></sub>
</div>
