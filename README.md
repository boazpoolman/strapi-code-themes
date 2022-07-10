<div align="center">
<h1>Strapi code themes</h1>
<p style="margin-top: 0;">Some coding inspired theme presets for Strapi CMS.</p>
<img src="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/showcase.gif" alt="Themes showcase" />
</div>

## ✨ Themes

- <a href="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/screenshots/githubDarkMode.png" target="_blank">Github dark mode</a>
- <a href="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/screenshots/monokai.png" target="_blank">Monokai</a>
- <a href="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/screenshots/nightOwl.png" target="_blank">Night owl</a>
- <a href="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/screenshots/oneDarkPro.png" target="_blank">One dark pro</a>
- <a href="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/screenshots/shadesOfPurple.png" target="_blank">Shades of purple</a>
- <a href="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/screenshots/synthwave.png" target="_blank">Synthwave</a>
- <a href="https://raw.githubusercontent.com/boazpoolman/strapi-code-themes/master/.github/screenshots/dracula.png" target="_blank">Dracula</a>

## ⏳ Installation

Install the package in your Strapi project.

```bash
# using yarn
yarn add strapi-code-themes

# using npm
npm install strapi-code-themes --save
```

## 💡 Usage

Inside the `/src/admin/app.js` file you can apply the theme to your Strapi installation. Add the following lines:

```
import themes from 'strapi-code-themes';

export default {
  config: {
    theme: {
      colors: themes.shadesOfPurple,
    },
  },
};
```

After setting up your theme you will have to rebuild you Strapi admin UI. To rebuild and restart Strapi run:

```bash
# using yarn
yarn build
yarn develop

# using npm
npm run build
npm run develop
```

Now you're all set. Enjoy your Strapi admin themes!

## 🤝 Contributing

Feel free to fork and make a pull request of this plugin. All the input is welcome!

## ⭐️ Show your support

Give a star if this project helped you.

## 📝 Resources

- [MIT License](LICENSE.md)
