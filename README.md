# meer

**meer** is a frameless desktop GitHub / GitLab repository browser for Windows.  
Browse public and private repositories, preview files, and download what you need — all from a clean, keyboard-friendly UI.

---

## Features

- **GitHub & GitLab** — supports GitHub.com, GitHub Enterprise, GitLab.com, and self-hosted GitLab
- **Public & private repos** — works without a token (public, 60 req/h) or with a PAT (private + 5,000 req/h)
- **File tree** — browse files in the root of any branch; multi-select with Click / Ctrl+Click / Shift+Click
- **File preview** — text, Markdown (with source toggle), and images
- **Download** — save individual files, folders, or the entire branch as a ZIP
- **Drag & drop** — drag selected files directly to Windows Explorer
- **Right-click menu** — Download / Open from context menu
- **Double-click / Enter** — open file with the OS default application
- **Search / filter** — type to filter the file list instantly
- **Light & Dark mode** — follows your Windows theme or set manually
- **Multilingual UI** — English / 日本語 / Español
- **Rate-limit badge** — remaining API requests shown in the status bar
- **Frameless window** — custom title bar; min / max / close controls

---

## Installation

Install from the **Microsoft Store** (recommended) or download the installer from [Releases](../../releases).

---

## Quick start

1. Launch meer.
2. Select a provider (**GitHub** or **GitLab**).
3. _(Optional)_ Open Settings, paste a Personal Access Token, and click **Save**.  
   - GitHub token scope: `repo`  
   - GitLab token scope: `read_api`
4. Enter a username or org name and click **Connect**.
5. Pick a **Repository** and a **Branch**.
6. Browse, preview, and download files.

---

## Privacy

meer does **not** collect any telemetry or user data. Your PAT is encrypted locally with Windows DPAPI and never transmitted to the developer. See [PRIVACY.md](PRIVACY.md) for details.

---

## License

[MIT](LICENSE) © 2026 misstouch-taro
