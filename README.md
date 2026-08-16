# cloud-native.io — Interactive Infrastructure Cheatsheet & Handbook

![Docs](https://img.shields.io/badge/Docs-Kubernetes%20%7C%20Docker%20%7C%20VMware%20%7C%20SSH-blue)
![Environment](https://img.shields.io/badge/Environment-Local%20%7C%20AWS-green)
![Tools](https://img.shields.io/badge/Tools-Minikube%20%7C%20Swarm%20%7C%20vmrun%20%7C%20SSH-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Interactive UI](https://img.shields.io/badge/Interactive%20UI-Production--Grade-2563EB)

DevOps.io is an interactive, production-grade web application cheat sheet and reference handbook for modern infrastructure management, container orchestration, virtual machine automation, and secure SSH provisioning.

---

## Features

### Design System & Aesthetics
- **100% Sharp Corner Reset**: Strictly enforced `border-radius: 0px !important` across all buttons, cards, inputs, selects, badges, toasts, headers, and footers.
- **Curated Color Palette**: Electric Blue primary accent (`#2563EB`), Pure Deep Black background (`#0B0C10`), Dark Slate (`#141720`), Dark Card (`#1A1E2B`), Input (`#0F1118`), Clean White (`#FFFFFF`), and Slate Border (`#CBD5E1`).
- **Typography & Syntax Highlighting**: Google Fonts `'Roboto Mono'` for command syntax and `'Inter'` for UI/headers. Token highlights for commands (`#60A5FA`), flags (`#F472B6`), comments (`#8292AA`), parameters (`#38BDF8`), and variables (`#A7F3D0`).
- **Vector Icons Policy**: Clean inline SVG vector icons across all categories and buttons (no emojis).

### Interactive Web App Features
- **Top Navigation Header**:
  - Brand logo with title (`DevOps.io`) and accent badge (`Handbook`).
  - Global search bar with `/` focus trigger and `Esc` clear shortcut.
  - `Quick Core` button copying essential daily commands in one click.
  - **Top-Right Favorites Toggle Button**: Star icon button toggling bookmarked favorites view on/off with gold active state.
  - Dark / Light mode toggle button and GitHub repository link.
  - Consistent 38px button height and vertical alignment across all action items.
- **Quick Goal Recipes Bar**: Horizontal scrollable bar with 1-click action chips (`Bootstrap Control Plane`, `Launch Minikube`, `Init Swarm`, `Start Headless VM`, `Generate SSH Key`, `Deploy Flannel`).
- **Synchronized Sidebar Controls**:
  - `Workflow Groups` dropdown with live command counts.
  - `Jump to Section` dropdown listing all numbered sections.
  - In-place dropdown synchronization with zero scroll jump and zero flicker.
  - Custom right-aligned SVG chevron down arrows (`right 12px center`).
- **Main Content View**:
  - Header Banner displaying category/section titles & descriptions.
  - View Switcher: **Cards Grid View** (semi-bold titles) & **Compact Table View** (`STAR`, `COMMAND TITLE` regular font weight, `CODE SYNTAX`, `DESCRIPTION`, `ACTION`).
  - 1-Click Copy buttons powered by safe `data-id` event delegation (preventing HTML attribute quote escaping issues) with toast feedback (`"Copied!"`).
  - Bookmark star toggle persisting user favorites in browser `localStorage`.
  - Empty State indicator when search query matches nothing.
- **Interactive Command Generator**:
  - Configurable parameters (Command Type, Host/Master IP, Key/VMX Path/Service Replicas).
  - Live command output box with terminal prompt (`>_`) icon and 1-click copy button.

---

## Quick Start

To launch the web application locally on your machine:

### Option 1: Python HTTP Server (Recommended)
```bash
python3 -m http.server 8080
```
Open your browser and navigate to `http://localhost:8080`.

### Option 2: Node npx serve
```bash
npx serve .
```

---

## License

This repository is licensed under the [MIT License](./LICENSE).
