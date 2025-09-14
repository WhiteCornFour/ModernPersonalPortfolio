# Personal Portfolio

A modern, responsive personal portfolio website built with **React**, **Vite**, and **Tailwind CSS**.

## Features

- ⚡️ Fast development with [Vite](https://vitejs.dev/)
- 🎨 Beautiful UI with [Tailwind CSS](https://tailwindcss.com/)
- 🌙 Light/Dark theme toggle
- ✨ Animated star and meteor background
- 🧭 Smooth navigation with sticky Navbar and scroll-to-section
- 📄 About, Skills, Projects, and Contact sections
- 📱 Responsive design for all devices
- 🔗 Social links and contact form

## Project Structure

```
.
├── public/
│   ├── vite.svg
│   └── projects/
│       └── story.png
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── AboutSection.jsx
│   │   ├── ContactSection.jsx
│   │   ├── Footer.jsx
│   │   ├── HeroSection.jsx
│   │   ├── Navbar.jsx
│   │   ├── ProjectsSection.jsx
│   │   ├── SkillsSection.jsx
│   │   ├── StarBackground.jsx
│   │   └── ThemeToggle.jsx
│   ├── lib/
│   │   └── utils.js
│   └── pages/
│       ├── Home.jsx
│       └── NotFound.jsx
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
└── README.md
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) >= 18.x
- [npm](https://www.npmjs.com/) >= 9.x

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/your-portfolio.git
   cd your-portfolio
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Start the development server:**

   ```sh
   npm run dev
   ```

4. **Open your browser:**  
   Visit [http://localhost:5173](http://localhost:5173) to view your portfolio.

### Build for Production

```sh
npm run build
```

### Preview Production Build

```sh
npm run preview
```

### Lint the Code

```sh
npm run lint
```

## Customization

- **Edit your information:**  
  Update your details in the components inside [`src/components/`](src/components/) and [`src/pages/Home.jsx`](src/pages/Home.jsx).
- **Add projects:**  
  Modify the `projects` array in [`ProjectsSection.jsx`](src/components/ProjectsSection.jsx).
- **Change skills:**  
  Edit the `skills` array in [`SkillsSection.jsx`](src/components/SkillsSection.jsx).
- **Update social links:**  
  Edit the links in [`ContactSection.jsx`](src/components/ContactSection.jsx).

## Technologies Used

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)
- [React Router](https://reactrouter.com/)

## License

This project is open source and available under the [MIT License](LICENSE).

---

> Inspired by modern portfolio designs.  
> Made with ❤️ by Hoang Nam.
