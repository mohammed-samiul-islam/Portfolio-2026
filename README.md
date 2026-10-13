# Portfolio 2026 – Mohammed Samiul Islam

Personal developer portfolio site built with React, Vite and Tailwind CSS.

## Features

- Single-page layout with Navbar, Hero, About, Projects, Experience, Contact and Footer sections
- Projects section linking to live demos and GitHub repos (PetSoft, Evento, rmtDev, and more)
- Contact form that submits to the [Web3Forms](https://web3forms.com) API
- Icons via `lucide-react`
- (A Testimonials section exists but is currently disabled in `App.jsx`.)

## Tech Stack

React · Vite · Tailwind CSS (v4, `@tailwindcss/vite`) · lucide-react · ESLint

## Project Structure

```
src/
  App.jsx            # page composition
  layout/            # Navbar, Footer
  sections/          # Hero, About, Projects, Experience, Testimonials, Contact
  components/        # Button, AnimatedBorderButton
index.html
vite.config.js
```

## Getting Started

```bash
npm install
npm run dev       # start dev server
npm run build     # production build to dist/
npm run preview   # preview the build
npm run lint
```

### Environment Variables

| Name | Purpose |
|------|---------|
| `VITE_WEB3FORMS_ACCESS_KEY` | Web3Forms access key for the contact form |

Create a `.env` file with this variable (do not commit it).

## License

See [LICENSE](LICENSE).
