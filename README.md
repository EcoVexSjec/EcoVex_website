# EcoSjec

![EcoSjec Logo](./public/logo.png)

Welcome to the EcoSjec website! This is an Astro-powered site for Eco SJEC, an environmental initiative focused on sustainability and eco-friendly projects at SJEC (St Joseph Engineering College).

## About

EcoSjec is dedicated to promoting environmental awareness, organizing eco-friendly events, and showcasing innovative projects that contribute to a greener future. Our website serves as a platform to connect with our team, explore our initiatives, and stay updated on upcoming events.

## Features

- **Home Page**: Introduction to Eco SJEC and our mission.
- **Team**: Meet the dedicated members driving our environmental efforts.
- **Projects**: Discover the innovative eco-projects we've undertaken.
- **Events**: Stay informed about our upcoming events and past activities.

## Project Structure

```
/
├── public/
│   └── (static assets like images, icons)
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Events.astro
│   │   ├── Eventslider.astro
│   │   ├── Footer.astro
│   │   ├── Group.astro
│   │   ├── Hero.astro
│   │   ├── Nav.astro
│   │   ├── Project.astro
│   │   └── Teampage.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       ├── team.astro
│       ├── projects.astro
│       └── event.astro
├── astro.config.mjs
├── package.json
├── tsconfig.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/royprince12-code/EcoVex_Sjec.git
   cd EcoVex_Sjec
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the development server:

   ```sh
   npm run dev
   ```

   Open [http://localhost:4321](http://localhost:4321) in your browser to view the site.

### Build for Production

```sh
npm run build
```

This will generate a `dist/` folder with the production build.

### Preview the Build

```sh
npm run preview
```

## Deployment

This site is configured for deployment to GitHub Pages. The site URL is set in `astro.config.mjs`.

To deploy:

1. Push your changes to the `main` branch.
2. GitHub Actions will automatically build and deploy the site (if workflow is set up).

## Contributing

We welcome contributions! Please feel free to submit issues or pull requests.

## License

This project is open-source. Check the license file for details.

## Learn More

- [Astro Documentation](https://docs.astro.build)
- [Astro Discord](https://astro.build/chat)
