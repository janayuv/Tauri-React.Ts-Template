# Tauri‑React.ts Template

**Built with**: Tauri 2.0 · React · TypeScript · Vite · TailwindCSS · Shadcn UI

A production-ready boilerplate for building cross-platform desktop apps with **Tauri v2**, offering modern tooling, styling, and UI components out of the box.

---

## Features

- **Tauri v2**: Leverage the latest stable version of Tauri for lightweight, secure desktop applications across Windows, macOS, and Linux.
- **React + TypeScript**: Statically typed and performant frontend built with React and TypeScript.
- **Vite**: Fast development and optimized builds using Vite as the build tool.
- **TailwindCSS**: Utility-first styling quickly customizing your UI.
- **Shadcn UI**: Modular, accessible UI components for rapid interface development.
- **ESLint with Type-Aware Rules**: Encourages code consistency, quality, and maintainability.

---

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- Rust toolchain (install via `rustup`)
- Optional but helpful: `pnpm` package manager

---

## Development Workflow

1. **Clone this repository**  
   ```bash
   git clone https://github.com/janayuv/Tauri-React.Ts-Template.git
   cd Tauri-React.Ts-Template
   ```

2. **Install dependencies**  
   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Run the application in development mode**  
   ```bash
   npm run tauri:dev
   # or
   pnpm tauri dev
   ```

---

## Build for Production

Generate a distributable package:

```bash
npm run tauri:build
# or
pnpm tauri build
```

---

## Getting Started (Manual Scaffold)

You can also initialize a similar setup using Tauri’s official scaffolding: `create-tauri-app` with the `react-ts` template, then integrate TailwindCSS and Shadcn manually.

---

## Recommended Tooling

- **IDE**: [Visual Studio Code](https://code.visualstudio.com/)
- **Plugins**:
  - Rust support: `rust-analyzer`
  - Tauri dev tools: `tauri-vscode`
  - ESLint for linting and code quality

---

## Project Structure (Highlights)

```
.
├── public/
├── src/             # React frontend
├── src‑tauri/       # Tauri backend (Rust + configuration)
├── package.json
├── vite.config.ts
├── tsconfig.json
├── eslint.config.js
└── …others…
```

---

## Contributing

Contributions welcome! Please:

1. Fork the repository  
2. Create a feature branch (`git checkout -b feature/xyz`)  
3. Commit your changes (`git commit -m "Add feature"`)  
4. Push to your fork (`git push origin feature/xyz`)  
5. Open a Pull Request describing your enhancements

---

## License

Distributed under the **MIT License** — see [LICENSE](./LICENSE) for details.

---

## Acknowledgments

- Powered by **Tauri** for building cross-platform desktop apps efficiently.
- Styled with **TailwindCSS** and **Shadcn UI** for rapid, beautiful UI development.

---

> Building desktop apps has never been this smooth. Enjoy creating with Tauri and React!
