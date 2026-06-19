# ZeroGrav Prompt Vault

> This repository is a fork of [asparks1987/ZeroGrav.dev](https://github.com/asparks1987/ZeroGrav.dev) created solely to make the site work cleanly on GitHub Pages and provide a usable online view of the webpage.

A high-performance, single-page prompt vault featuring 250 execution-grade prompts for engineering, design, and deployment.

This fork keeps the same core experience as the upstream project, but is maintained specifically for GitHub Pages compatibility and browser-friendly static hosting.

---

## Why This Exists

Most prompts are vague, one-shot afterthoughts - and the output shows it. ZeroGrav is a curated vault of **250 production-grade prompts** built for people who ship with AI, not just chat with it.

- **Copy. Paste. Ship.** Every prompt is a complete, structured payload - not a starting point you have to fix. Paste it, get implementation-ready output on the first try.
- **Find what you need in seconds.** Instant search, category filter pills, and one-click copy - no docs to read, no setup, no login.
- **Built for the way vibe coders actually work.** Modal-based detail views keep you in flow. Open a card, grab the prompt, close it, keep building.

## Key Features

- **250 Engineered Prompts**: Covering 10 critical categories including UX, Performance, and Accessibility.
- **One-Click Workflows**: Copy and share prompts individually or share the entire vault.
- **Premium Aesthetics**: Glassmorphic UI with responsive typography and micro-animations.

## Project Structure

```text
.
|-- index.html      # Core page structure and SEO metadata
|-- styles.css      # Premium visual system and card layout
|-- script.js       # Dataset, filtering logic, and share behavior
`-- assets/         # Branding and iconography
```

## Local Development

Clone the repository and spin up a local server:

```bash
git clone <this-repository-url>
cd ZeroGrav.dev
python -m http.server 4173
```

Navigate to `http://localhost:4173` to see it in action.

## Contributing

Contributions are welcome. If you plan to change behavior here, please keep in mind that this fork exists specifically to support GitHub Pages deployment.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m "Add some AmazingFeature"`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

*Built for speed. Engineered for precision.*
