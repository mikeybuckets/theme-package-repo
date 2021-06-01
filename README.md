# Tailwind CSS Landing Page Next JS React

If you are looking for a Theme focused on SIMPLICITY and FLEXIBILITY, Tailwind CSS Landing Page Next JS is the perfect Tailwind theme to start your project. The theme contains components that are fully responsive and easy to configure built with React, Next.js, Tailwind CSS and TypeScript.

The theme is highly customizable and developer friendly: the theme follows a consistent coding style and frontend architecture.

### Features

- Simplicity
- Fully responsive design
- High-quality code
- Great performance
- Highly customizable design
- Full documentation
- Cross-Browser compatibility
- Unique Landing Page
- Combined UI blocks
- Templates Styled with Tailwind CSS
- 10+ Designs Blocks and 17+ Components

Developer experience first:

- 🔥 [Next.js](https://nextjs.org) for Static Site Generator
- 🎨 Integrate with [Tailwind CSS](https://tailwindcss.com)
- 💅 [PostCSS](https://postcss.org) for processing [Tailwind CSS](https://tailwindcss.com)
- 🎉 Type checking [TypeScript](https://www.typescriptlang.org)
- ✏️ Linter with [ESLint](https://eslint.org)
- 🛠 Code Formatter with [Prettier](https://prettier.io)
- 🦊 SEO metadata, [JSON-LD](https://developers.google.com/search/docs/guides/intro-structured-data) and [Open Graph](https://ogp.me/) tags with [Next SEO](https://github.com/garmeeh/next-seo)

Built-in feature from Next.js:

- ☕ Minify HTML & CSS
- 💨 Live reload
- ✅ Cache busting

### Philosophy

- Minimal code
- SEO-friendly
- 🚀 Production-ready

### Included Components

- Navbar
- Hero
- Statistics
- Features (2+ types)
- Testimonial
- Pricing card
- FAQ
- Newsletter form
- Footer

### Requirements

- Node.js and npm

### Getting started

Run the following command on your local environment:

```
npm run dev
```

Open http://localhost:8080 with your favorite browser to see your project. For your information, Next JS need to take some time to compile the project for your first time.

```
.
├── README.md            # README file
├── public
│   └── assets
│       └── images       # Image used by the template, it can be replaced by your own images
├── src
│   ├── background       # Atomic background component
│   ├── button           # Atomic button component
│   ├── faq              # Atomic faq component
│   ├── feature          # Atomic feature component
│   ├── footer           # Atomic footer component
│   ├── form             # Atomic form component
│   ├── hero             # Atomic hero component
│   ├── layout           # Atomic layout component
│   ├── navigation       # Atomic navigation component
│   ├── pages            # Next JS pages includes index page
│   ├── pricing          # Atomic pricing component
│   ├── stats            # Atomic stats component
│   ├── styles           # Atomic styles component
│   ├── template         # List of blocks components
│   ├── testimonial      # Atomic testimonial component
│   └── utils            # Atomic utils component
├── tailwind.config.js   # Tailwind CSS configuration file
└── tsconfig.json        # TypeScript file
```

### Customization

You can easily configure the theme. Please change the following file:

- `public/apple-touch-icon.png`, `public/favicon.ico`, `public/favicon-16x16.png` and `public/favicon-32x32.png`: your favicon, you can generate from https://favicon.io/favicon-converter/
- `src/styles/main.css`: your CSS file using Tailwind CSS
- `utils/Config.ts`: website configuration file
- `src/pages/index.tsx`: the index page of the theme use the `Base` component
- `src/template/Base.tsx`: the `Base` component using component blocks
- `src/template/*`: the list of component blocks
- `src/*`: other folders in src are the atomic components used by components blocks

Here is the layer:

- the entry point: `index.tsx` in `src/pages`
- the `Base` template: `Base.tsx` in `src/template`
- use component blocks from `src/template/*`
- use atomic components from `src/*`

### Deploy to production

You can see the results locally in production mode with:

```
$ npm run build
$ npm run start
```

The generated HTML and CSS files are minified (built-in feature from Next js). It will also removed unused CSS from [Tailwind CSS](https://tailwindcss.com).

You can create an optimized production build with:

```
npm run build-prod
```

Now, your theme is ready to be deployed. All generated files are located at `dist` folder, which you can deploy with any hosting service.

---

Made with ♥ by [CreativeDesignsGuru](https://creativedesignsguru.com)
