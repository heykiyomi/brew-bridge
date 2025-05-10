# 🍵 brew-bridge

**brew-bridge** is a universal package indexing utility that leverages [Tea](https://tea.xyz/) to discover and manage open source projects across 7 major ecosystems:
**APT**, **Crates (Rust)**, **Homebrew**, **npm**, **PyPI**, **RubyGems**, and **pkgx**.

## ✨ Features

* 🧩 Unified search across all supported ecosystems
* 🔍 Discover trending and new open-source projects
* 🛠️ Generate Tea-compatible metadata for any project
* ⚡ Lightweight CLI built with Node.js and Rust
* 📦 Built-in support for automated version sync with Tea

## 🧪 Supported Ecosystems

* ✅ APT (Debian/Ubuntu)
* ✅ Crates (Rust)
* ✅ Homebrew (macOS/Linux)
* ✅ npm (JavaScript/Node.js)
* ✅ PyPI (Python)
* ✅ RubyGems (Ruby)
* ✅ pkgx (Cross-platform package runner)

## 🚀 Getting Started

### Installation

```bash
npm install -g brew-bridge
```

Or run it directly with pkgx:

```bash
pkgx brew-bridge
```

### Usage

```bash
brew-bridge search express     # Searches for 'express' in all ecosystems
brew-bridge link npm express  # Links express npm package to Tea
```

### Example Output

```bash
🔍 Searching for "express"...
✅ npm      | express       | Fast, unopinionated web framework
✅ PyPI     | flask         | Lightweight Python web framework
✅ RubyGems | sinatra       | DSL for quickly creating web applications
...
```

## 🛠 Built With

* Rust (for ecosystem scraping)
* Node.js (CLI interface)
* Tea SDK
* TypeScript

## 📦 Project Structure

```
/cli         # CLI interface (Node.js + TypeScript)
/scraper     # Rust-based scraper for ecosystem data
/utils       # Shared utilities
```

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a PR.

1. `git clone https://github.com/your-username/brew-bridge.git`
2. `cd brew-bridge`
3. `npm install`
4. `npm run dev`

## 🧑‍💻 Author

Made with ☕ by Kiyomi

## 🪪 License

MIT License
