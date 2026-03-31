# Sumedh Jaltare Portfolio

Modern developer portfolio built with React + Vite and styled with Tailwind CSS.

## Highlights

- Dark mode by default + light mode toggle
- Fully responsive, mobile-first layout
- Smooth animations with Framer Motion
- Component-based structure
- GitHub Pages-ready deployment setup

## Sections Included

- Hero
- About
- Skills
- Projects
- GitHub
- Experience
- Achievements
- Education
- Contact

## Tech Stack

- React 19
- Vite 8
- Tailwind CSS 3
- React Router
- Framer Motion
- GitHub REST API

## Project Structure

```text
src/
	components/
		Navbar.jsx
		Hero.jsx
		About.jsx
		Skills.jsx
		Projects.jsx
		ProjectCard.jsx
		GitHubSection.jsx
		Experience.jsx
		Achievements.jsx
		Education.jsx
		Contact.jsx
		SectionHeader.jsx
	pages/
		Home.jsx
	lib/
		githubApi.js
	App.jsx
	main.jsx
```

## Local Development

```bash
npm install
npm run dev
```

Open: `http://localhost:5173`

## Scripts

- `npm run dev` — start development server
- `npm run build` — create production build
- `npm run preview` — preview production build locally
- `npm run lint` — run lint checks
- `npm run deploy` — deploy `dist` to GitHub Pages using `gh-pages`

## Environment Variables (Optional)

Create a `.env` file in the root only if needed:

```env
VITE_GITHUB_USERNAME=sumedh-jaltare
VITE_GITHUB_TOKEN=your_optional_github_token
```

- `VITE_GITHUB_USERNAME` defaults to `sumedh-jaltare`
- `VITE_GITHUB_TOKEN` helps avoid GitHub API rate limits

## GitHub Pages Notes

- Vite base path is configured for a repo deployment (`/portfolio/`).
- Router is configured with `HashRouter` for GitHub Pages compatibility.

Deploy:

```bash
npm run build
npm run deploy
```

Default deploy target:

`https://github.com/sumedh-jaltare/portfolio.git`
