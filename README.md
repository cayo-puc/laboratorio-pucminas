🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎮 Soc Ops

### **Social Bingo for In-Person Mixers**

*Find people who match the questions and get 5 in a row!*

**Master GitHub Copilot Agent Mode while building an awesome game** 🤖

[![Java](https://img.shields.io/badge/Java-21-orange?logo=java)](https://adoptium.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.2-green?logo=spring-boot)](https://spring.io/projects/spring-boot)
[![Maven](https://img.shields.io/badge/Maven-3.9%2B-blue?logo=apache-maven)](https://maven.apache.org/)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

[🚀 Start the Lab](#-quick-start) • [📖 Full Guide](workshop/GUIDE.md) • [✨ Features](#-features)

</div>

---

## ✨ What is Soc Ops?

**Soc Ops** is a hands-on learning experience that combines two awesome things:

🎯 **A Fun Game** — An interactive Social Bingo app that breaks the ice at in-person events. Players find people who match specific prompts and race to get 5 in a row. Perfect for team events, conferences, and mixers!

🤖 **An AI Mastery Workshop** — Learn to harness the power of GitHub Copilot Agent Mode as you:
- Engineer context to teach AI about your codebase
- Design interfaces with AI-powered creativity
- Build features faster with agentic development patterns
- Level up your development workflow

---

## 🎯 What You'll Learn

| Skill | What You'll Do |
|-------|---------|
| **Context Engineering** | Teach AI about your codebase with custom instructions |
| **Agentic Development** | Use background agents, cloud agents, and custom workflows |
| **Design-First Development** | Let AI iterate on UI while you guide the vision |
| **Test-Driven Development** | Build reliable features with TDD agents |

---

## 🚀 Quick Start

### 1️⃣ Prerequisites

- [Java 21 JDK](https://adoptium.net/) or higher
- [Apache Maven 3.9+](https://maven.apache.org/) (or use the included Maven Wrapper)
- VS Code v1.107+ with GitHub Copilot
- Git

### 2️⃣ Run the Game

```bash
cd socops
./mvnw spring-boot:run
```

Then open `http://localhost:8080` in your browser and start playing! 🎉

### 3️⃣ Build & Test

```bash
# Build the project
cd socops && ./mvnw clean package

# Run tests
cd socops && ./mvnw test
```

---

## 📚 Lab Curriculum

Estimated time: **~1 hour** | Level: **Intermediate**

| Part | Topic | Time | What You'll Build |
|------|-------|------|---------|
| [**01**](workshop/01-setup.md) | Setup & Context Engineering | 15 min | Configure your workspace & teach AI about your code |
| [**02**](workshop/02-design.md) | Design-First Frontend | 15 min | Redesign the UI with creative themes |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master | 10 min | Create custom quiz themes with AI |
| [**04**](workshop/04-multi-agent.md) | Multi-Agent Development | 20 min | Build new features with TDD & design agents |

👉 **[Start the Lab Guide →](workshop/GUIDE.md)**

---

## 📁 Project Structure

```
├── socops/                 # Main Spring Boot application
│   ├── src/main/java/     # Game logic & REST API
│   ├── src/main/resources/templates/  # Game UI (HTML/CSS)
│   └── pom.xml            # Maven configuration
├── workshop/              # Interactive learning guide
└── docs/                  # Static documentation
```

---

## 🎮 How to Play

1. **Open the game** in your browser
2. **Read the prompt** in the bingo card
3. **Find people** who match each prompt
4. **Mark the cell** when you get their initials
5. **Get 5 in a row** (horizontal, vertical, or diagonal) to win! 🏆

---

## 🔧 Technology Stack

- **Backend:** Java 21 + Spring Boot 3.4.2
- **Frontend:** HTML5 + CSS3 (vanilla JS)
- **Build:** Apache Maven
- **Deployment:** GitHub Pages (automatic on `main` branch)

---

## 📝 Lab Guides

All guides are available both here and in the [`workshop/`](workshop/) folder for offline reading:

- 📖 [Overview & Checklist](workshop/00-overview.md)
- 🛠️ [Setup & Context Engineering](workshop/01-setup.md)
- 🎨 [Design-First Frontend](workshop/02-design.md)
- 🤖 [Custom Quiz Master](workshop/03-quiz-master.md)
- 🚀 [Multi-Agent Development](workshop/04-multi-agent.md)

---

## 💡 Pro Tips

✅ Keep your browser open to watch live updates as you code

✅ Commit frequently to save working states

✅ Use chat Checkpoints & Undo for quick recovery

✅ Pin this guide while you work

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📞 Support

Check [SUPPORT.md](SUPPORT.md) for help and resources.
