# Laserzahnarzt Laatzen Website

Modern website for Laserzahnarzt Laatzen built with Astro and Tailwind CSS v4.

## ⚡ Tech Stack

- **Framework:** Astro (Static Site Generator)
- **Styling:** Tailwind CSS v4
- **TypeScript:** Full type safety
- **Package Manager:** npm
- **Deployment:** Static hosting ready

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/              # Static assets (images, favicon, etc.)
├── src/
│   ├── components/      # Astro components
│   ├── content/         # Content collections (blog, etc.)
│   ├── layouts/         # Page layouts
│   ├── pages/           # Routes (file-based routing)
│   └── styles/          # Global CSS and Tailwind config
├── astro.config.mjs     # Astro configuration
├── CLAUDE.md           # Claude Code project instructions
└── package.json
```

- **Pages:** Astro looks for `.astro` or `.md` files in `src/pages/` - each file becomes a route
- **Components:** Reusable Astro components in `src/components/`
- **Layouts:** Base page templates in `src/layouts/`
- **Content:** Markdown content with frontmatter in `src/content/`
- **Styles:** Global CSS and Tailwind configuration in `src/styles/`
- **Static Assets:** Images, fonts, and other static files in `public/`

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run lint`            | Run ESLint to check code quality                 |
| `npm run format`          | Format code with Prettier                        |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone git@github.com:uplantic/laserzahnarzt.git
   cd laserzahnarzt
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to `http://localhost:4321`

## 🏗️ Building for Production

```bash
npm run build
```

The built site will be in the `./dist/` directory, ready for deployment to any static hosting service.

## 📝 Development Guidelines

- Follow the conventions outlined in `CLAUDE.md`
- Use Tailwind utility classes for styling
- Keep components simple and focused
- Optimize images before adding to `public/`
- Run `npm run lint` and `npm run format` before committing

## 🌐 Deployment

This project generates a static site that can be deployed to:
- Netlify
- Vercel
- GitHub Pages
- Any static hosting service

## 📚 Resources

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS v4 Documentation](https://tailwindcss.com/docs)
- [Project Guidelines](./CLAUDE.md)
