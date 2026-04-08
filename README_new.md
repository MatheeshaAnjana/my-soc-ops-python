<div align="center">

🌐 **Languages:** [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

---

# 🎲 Soc Ops

### The Icebreaker Game That Actually Works

**Break the ice at mixers and networking events with Social Bingo—a fun, interactive game where you mingle, find people who match fun questions, and race to get 5 in a row!**

<img src="https://img.shields.io/badge/Python-3.13+-blue.svg" alt="Python 3.13+">
<img src="https://img.shields.io/badge/FastAPI-0.115+-brightgreen.svg" alt="FastAPI">
<img src="https://img.shields.io/badge/License-MIT-purple.svg" alt="MIT License">

[🎮 Play Online](#-quick-start) • [📖 Learn More](#-what-is-soc-ops) • [🛠️ Getting Started](#-setup) • [📚 Lab Guide](#-lab-guide)

</div>

---

## 🎯 What is Soc Ops?

Tired of awkward silences at networking events? **Soc Ops** is a social bingo game designed to help people connect at in-person mixers and conferences.

### How It Works

1. **🎴 You get a bingo card** with 25 fun questions like "has lived in another country" or "speaks more than 2 languages"
2. **👥 You mingle and find people** who match each square
3. **✅ Mark them off** as you find matches
4. **🎉 Get 5 in a row** (horizontal, vertical, or diagonal) to win!

### Why It Works

- 🔥 **Breaks the ice naturally** — people have to talk to strangers
- 🎯 **Creates meaningful conversations** — questions spark genuine discussion
- ⚡ **Quick to learn, fun to play** — anyone can join in immediately
- 🏆 **Built-in competitive element** — first to bingo wins!

---

## 🎮 Quick Start

### Prerequisites
- **Python 3.13+**
- **[uv](https://docs.astral.sh/uv/)** package manager

### Run the Game

```bash
# Clone and navigate to the project
git clone <repo-url>
cd soc-ops

# Install dependencies
uv sync

# Start the server
uv run soc-ops
```

Then open **[http://localhost:8000](http://localhost:8000)** in your browser and start playing! 🎲

---

## 🏗️ Tech Stack

Built with modern Python tools for a smooth development experience:

| Component | Technology |
|-----------|-----------|
| **Framework** | FastAPI — Fast, modern, async-ready |
| **Frontend** | Jinja2 + HTMX — Interactive without JavaScript bloat |
| **Package Manager** | uv — Lightning-fast Python dependency management |
| **Linting** | Ruff — Blazingly fast Python linter |
| **Testing** | pytest — Simple, powerful testing framework |

---

## 📚 Lab Guide

This project comes with a comprehensive workshop guide for learning by building!

| Part | Topic | Learn |
|------|-------|-------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist | Project structure & setup |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering | Configure your dev environment |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend | Build beautiful, responsive UI |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master | Create your own questions |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development | Use AI agents to enhance features |

💡 **Tip:** Lab guides are also available offline in the [`workshop/`](workshop/) folder.

---

## 🛠️ Setup

Want to set up a local development environment? Start here:

1. **Install dependencies:** `uv sync`
2. **Run tests:** `uv run pytest`
3. **Start dev server:** `uv run soc-ops` (auto-reloads on changes)
4. **Check code quality:** `uv run ruff check .`

For detailed setup instructions, see **[Part 01: Setup & Context Engineering](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup)**.

---

## 🧪 Project Structure

```
soc-ops/
├── app/                    # Application code
│   ├── main.py            # FastAPI server & routes
│   ├── models.py          # Game data models
│   ├── game_logic.py      # Bingo logic & board generation
│   ├── game_service.py    # Session management
│   └── static/            # CSS, images, fonts
├── tests/                 # Test suite
│   ├── test_api.py        # API tests
│   └── test_game_logic.py # Game logic tests
├── workshop/              # Lab guide (offline)
└── pyproject.toml         # Project config & dependencies
```

---

## 📖 Features

- ✅ **Responsive Design** — Works on desktop, tablet, mobile
- ✅ **Session-based** — Each player gets their own board
- ✅ **Real-time Updates** — HTMX for smooth interactions
- ✅ **Random Board Generation** — Fresh game every time
- ✅ **Win Detection** — Automatically detects bingo (rows, columns, diagonals)
- ✅ **Reset & Replay** — Play multiple rounds

---

## 🤝 Contributing

Have ideas to improve Soc Ops? We'd love your input! Check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

## 🙋 Support

Have questions or run into issues?

- 📖 Check the [workshop guides](workshop/) for detailed walkthroughs
- 📝 Review [SUPPORT.md](SUPPORT.md) for troubleshooting
- 🔒 See [SECURITY.md](SECURITY.md) for security guidelines

---

<div align="center">

**Made with ❤️ for breaking the ice and building connections.**

[⬆ Back to top](#-soc-ops)

</div>
