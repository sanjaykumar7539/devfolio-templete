# Devfolio Template

A customizable developer portfolio template built with Next.js, React, Tailwind CSS, MDX, and Framer Motion. It is designed for personal portfolios, project showcases, and blog-style content.

## Features

- Responsive portfolio layout
- Dynamic projects and blog content
- MDX-based blog writing
- Theme presets and custom color choices
- Contact form via Resend
- Vercel-friendly deployment flow

## Requirements

- Node.js
- npm

## Run locally

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm start
```

## Project customization

Key config files:

- `src/config/siteConfig.ts`
- `src/config/themePresets.ts`
- `src/contents/projects.ts`

The repo also includes Markdown guides for site customization and MDX blog writing under the `docs/` folder.

## Deployment

This template is designed for deployment on Vercel. If you enable the contact form, configure the required environment variables before deploying.

## License

The repository uses the MIT License. Confirm upstream attribution and dependency terms before publishing a fork or derivative project.
