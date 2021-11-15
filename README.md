<div align="center">
<h1>Strapi code themes</h1>
<p style="margin-top: 0;">Some coding inspired theme presets for Strapi CMS.</p>
<img src="https://github.com/boazpoolman/strapi-code-themes/tree/master/.github/showcase.gif" alt="Themes showcase" />
</div>

## ✨ Themes

- [Github dark mode](https://github.com/boazpoolman/strapi-code-themes/tree/master/.github/screenshots/githubDarkMode.png)
- [Monokai](https://github.com/boazpoolman/strapi-code-themes/tree/master/.github/screenshots/monokai.png)
- [Night owl](https://github.com/boazpoolman/strapi-code-themes/tree/master/.github/screenshots/nightOwl.png)
- [One dark pro](https://github.com/boazpoolman/strapi-code-themes/tree/master/.github/screenshots/oneDarkPro.png)
- [Shades of purple](https://github.com/boazpoolman/strapi-code-themes/tree/master/.github/screenshots/shadesOfPurple.png)
- [Synthwave](https://github.com/boazpoolman/strapi-code-themes/tree/master/.github/screenshots/synthwave.png)

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
import { monokai } from 'strapi-code-themes';

export default {
  config: {
    theme: {
      colors: monokai,
    },
  },
};
```

Now you're all set. Enjoy your Strapi admin themes!

## 🤝 Contributing

Feel free to fork and make a pull request of this plugin. All the input is welcome!

## ⭐️ Show your support

Give a star if this project helped you.

## 📝 Resources

- [MIT License](LICENSE.md)
