# README Icon Arrangement

This file explains how the `README.md` icons are organized.

- Operating Systems: operating system icons.
- Languages: core programming languages and runtimes.
- Frontend & Web: markup, styling, UI, and browser frameworks.
- Frameworks & Stacks: frontend frameworks, backend frameworks, databases, and app stacks.
- Deployment & Servers: servers, containers, hosting, and deployment platforms.
- AI & Automation: AI platforms, AI assistants, and automation tools.
- Data & Machine Learning: data science and ML tooling.
- Tools & IDEs: development tools, editors, and environment utilities.
- Standalone Tools: individual product tools that do not fit a broader visible section. This section is currently commented out.
- Hardware & Maker: embedded and maker platform icons.
- Payments & Blockchain: finance, payment processors, and blockchain brands.
- Integrations: business/API integrations and external service platforms.

The README now uses commented section labels instead of visible headings, so the profile page shows logos only with no section text.

Icons use SVG sources from devicons, Simple Icons, the lobehub/lobe-icons repo, the bwks/vendor-icons-svg repo, the gilbarbara/logos repo, worldvectorlogo.com, and verified official brand assets. Most integration icons are wrapped in links with hover titles for quick reference.

Additional notes:
- AI & Automation order: `n8n`, `Claude`, `OpenAI`, `MCP`, `Groq`.
- Tools & IDEs order: `VSCode`, `Bash`, `GitHub`, `Android Studio`.
- Payments & Blockchain order: `PayPal`, `Stripe`, `Authorize.net`, `Ethereum`, `Binance / BNB`.
- Deployment & Servers order: `Docker`, `Nginx`, `AWS`, `Cloudflare`, `Vercel`, `Netlify`, `cPanel`, `XAMPP`.
- Integrations use developer/app platform links: `Google Cloud`, `Meta for Developers`, `LinkedIn Developers`, and `Slack API`.
- `21st.dev` is kept in a commented Standalone Tools block because it is a tool and currently the only icon in that category.
- White-background icons are used selectively for logos that need contrast against the README background.
- GitHub README sanitizes inline HTML/CSS, so `style="background:#fff"` may not render on profile pages. Use a pre-rendered white-background image or a proxy image wrapper such as `wsrv.nl`.

Example:
- `![Icon](https://wsrv.nl/?url=YOUR_RAW_SVG_URL&bg=ffffff)`
