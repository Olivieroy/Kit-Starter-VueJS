<div align="center">
    <h1> Kit-Starter VueJs </h1>
    <p> A starter template for junior VueJs developper </p>
    <img src="https://cdn.discordapp.com/attachments/954117377593868331/1047879287275012176/kit-starter.png">
</div>

## Table of Contents π¨π»βπ«

1. [Table of Contents](#table-of-contents-π¨π»βπ«)
2. [Browser Support](#browser-support-π)
3. [Installation](#installation-π¦)
4. [Usage](#usage)
5. [Structure](#structure-π¨)
6. [License](#license-π)
7. [Autor](#autor)


## Browser Support π
- Chrome
- Firefox
- Safari
- Edge
- Opera

## Installation π¦
First step : clone the repository

```sh
$ git clone https://github.com/Olivieroy/web-starter.git
```

Second step : install the dependencies with npm

```sh
$ npm install sass
```

Third step : run the project.
Good Luck ! π

## Structure π¨

### Forlder structure

```
βββ .vscode π 
β   βββ extensions.json π   # Extensions for Vue in Vscode
β
βββ node_modules π       # Dependencies
β
βββ public π             # Public files
β   βββ favicon.ico π    # Favicon
β   β
β   βββ css π        # Css files
β   β   βββ master.css π  # Css file
β   β   β
β   β   βββ remove.css π  # Css file for remove
β   β
β   βββ img π        # Images
β   β
β   βββ  sass π                    # SASS folder
β       βββ libs π              # Libs folder
β       β   βββ _index.scss π        # Index file for libs
β       β   β
β       β   βββ _normalize.scss π        # Normalize file
β       β   β
β       β   βββ  _reset.scss π        # Reset file
β       β
β       βββ  master π              # SCSS file for the project to compiled 
β
βββ src π               # Source files
β   βββ components π        # Components folder
β   β   βββButton.vue π    # Button component
β   β
β   βββ layouts π        # Layouts folder
β   β   βββ Header.vue π    # Header component
β   β   β
β   β   βββ  Footer.vue π    # Footer component
β   β
β   βββ pages π        # Pages folder
β   β   βββ AboutView.vue π    # About page
β   β   β
β   β   βββ  ComponentsView.vue π    # Components page
β   β   β
β   β   βββHomeView.vue π    # Home page
β   β
β   βββ parts π        # Parts folder
β   β   βββ AboutHelp.vue π    # Help part
β   β   β
β   β   βββ  AboutProject.vue π    # Project part
β   β   β
β   β   βββCongralutation.vue π    # Congralutation part
β   β
β   βββ router π        # Router folder
β   β   βββindex.js π    # Router file
β   β
β   βββ  sass π                    # SASS folder
β   β  βββ global π              # Global folder
β   β  β   βββ _animations.scss π        # Animations file
β   β  β   β
β   β  β   βββ _breakpoints.scss π        # Breakpoints file
β   β  β   β
β   β  β   βββ _colors.scss π        # Colors file
β   β  β   β
β   β  β   βββ _fonts.scss π        # Fonts file
β   β  β   β
β   β  β   βββ _functions.scss π        # Functions file
β   β  β   β
β   β  β   βββ _icons.scss π        # Icons file
β   β  β   β
β   β  β   βββ _index.scss π        # Index file for global
β   β  β   β
β   β  β   βββ  _mixins.scss π        # Mixins file
β   β  β
β   β  βββ  master π              # SCSS file for the project to compiled in .vue file
β   β
β   βββ App.vue π      # App file
β   β
β   βββ main.js π      # Main file
β
βββ .eslintrc.cjs π       # Eslint file
β
βββ .gitignore π       # Gitignore file
β
βββ .prettierrc.json π       # Prettier file
β
βββ index.html π              # Index file for the project
β
βββ LICENSE π              # License file
β
βββ package-lock.json π                    # JSON file 
β
βββ package.json π                    # JSON file
β
βββ README.md π              # Readme file
β
βββvite.config.js π              # Vite config file
```





## Usage
- `npm run sass` : compile sass to css 
- `npm run dev` : run the project in development mode
<p> You can create another "npm run" command in the package.json file π </p>

## License
[MIT](https://github.com/Olivieroy/web-starter/LICENSE.) 

## Author
[Olivieroy](https://olivieroy.fr) π§’
