# Layout test. Laura González Calvo.

<div id="header" align="center">
  <img width="150"  src="https://images-na.ssl-images-amazon.com/images/S/stores-image-uploads-eu-prod/f/AmazonStores/A1RKKUPIHCS9HS/e2979d1497306e962d8d3ae4439cbd2c.w1200.h1200.jpg">
</div>

This exercise consists of developing a **basic and responsive layout**. For the company CREATE ikohs

## Design.

- Logo, typography and palette

<div id="header" align="center">
  <img width="260" height="260" src="imagen logo">
</div>

```bash
// fonts
$font-main: Arial, Helvetica, sans-serif;

// colors
$color-header-footer: #ff993e;
$color-links-bg: #c0392b;
$color-text: black;
$color-links: white;
$color-bg-main: white;
$color-grey: #c8c5c5;
$color-aside-bg: #008000;
$color-media-bg: #874000;
$color-links-hover: #e74c3c;
```

AÑADIR IMAGEN Y DESKTOP DE CREATE

## PROCESS

- Drawing a sketch
  PONER IMAGEN BOCETO
- Realization of the **HTML**. Taking into account the BEM methodology, variables...
- Realization of the **CSS**. Using CSS features like Grid, Flexbox, hovers, animations, mobile first..
- Thanks to **SASS**, I have been able to work with "variables" to define the colors of the page; "mixins" to define the tablet and computer version. "Partials" to work with different files

# FINAL RESULT

AÑADIR IMAGEN Y DESKTOP DE CREATE y tablet

- Mobile, below 500px
- Tablet, from 768px to 1200px
- Desktop, starting at 1200px

## Technologies:

- **HTML5**.
- **CSS**.
- **GitHub (branches,git...)**.
- Task automation: **Gulp**.
- Syntactically Awesome Stylesheet: **Sass**.
- Gestión de **eventos** en el navegador.
- **JSON**.
- **NodeJS**.
- **[Adalab - Web starter kit](https://github.com/Adalab/Adalab-web-starter-kit)**.

### Steps to follow every time you want to start a project from scratch:

- Install NodeJS if you don't have it. It is necessary.
- Create your own repository.
- Download the Starter kit from **[GitHub](https://github.com/Adalab/Adalab-web-starter-kit)**.
- Copies all the files in the root folder of the repository.
- Open a terminal and install the local dependencies by executing in the command terminal:

```bash
npm install
```

### Steps to start the project:

**The project must be started every time we start programming**, for this we will execute the command:

```bash
npm start
```

This command:

- **Opens a Chrome window and displays your web page**, just like the VS Code Live Server (Go live) plugin does.
- It also **watches** all the files inside the `src/` folder, so that every time you modify a file it **refreshes your page in Chrome**.
- It also **processes the HTML, SASS / CSS and JS files** and **generates and saves them in the `public/`** folder. For example:
  - Converts SASS files to CSS.
  - It combines the different HTML files and groups them into one or more HTML files.

After executing `npm start` we can start editing all the files that are inside the `src/` folder and programming comfortably.
