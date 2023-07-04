# Minimalist Portfolio
Single page portfolio made with [Astro](https://astro.build/)

![Minimalist Portfolio](/images/web.png)

## Demo
View a live demo: [slydragonn.velcel.app](https://slydragonn.vercel.app)

## Clone:
```
git clone https://github.com/slydragonn/minimalist-portfolio.git
```

## Install:

```
npm install
```

## Run:
```
npm run dev
```

## Project Struture
```
├── src/
│   ├── components/
│   │   ├── Button.astro
│   │   ├── Footer.astro
│   │   ├── Navbar.astro
│   │   ├── ProjectCard.astro
│   │   ├── SkillCard.astro
│   │   └── Title.astro
│   ├── pages/
│   │   └── index.astro
├── public/
│   ├── favicon.svg
│   ├── design.svg
│   ├── dragon.png
│   ├── email.svg
│   ├── external-link.svg
│   ├── python.svg
│   └── server.svg
├── astro.config.mjs
├── package.json
├── .gitignore
├── README.md
└── tsconfig.json
```

## Components

**Button:**
```
<Button
    message='Latest Posts'
    icon='/external-link.svg'
    link='https://dev.to/slydragonn'
/>
```

**Title:**
```
<Title 
    text='Skilss & Technologies'
/>
```

**SkillCard:**
```
<SkillCard 
	title='Frontend Development'
	description='Developing websites with JavaScript and the best Frameworks like React, Vue, and Astro'
	icon='/design.svg'
/>
```

**ProjectCard:**
```
<ProjectCard 
	title='Markdown Web Editor'
	description='Simple and Minimalist Markdown Web Editor'
	link='https://markwriter.tech'
/>
```

## Deploy
You can deploy this site on your favorite static hosting service such as Vercel, Netlify, GitHub Pages, etc.

