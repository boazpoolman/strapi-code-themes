<div align="center">
<h1>Strapi code themes</h1>
<p style="margin-top: 0;">Some coding inspired theme presets for Strapi CMS.</p>
</div>

## ✨ Themes

- Github dark mode
- Monokai
- Night owl
- One dark pro
- Shades of purple
- Synthwave

## ⏳ Installation

Install the package in your Strapi project.

```bash
# using yarn
yarn add strapi-code-themes

# using npm
npm install strapi-code-themes --save
```

Enjoy 🎉

## 🖐 Requirements

Complete installation requirements are the exact same as for Strapi itself and can be found in the [Strapi documentation](https://strapi.io/documentation).

**Supported Strapi versions**:

- Strapi v4.0.0-beta.12 (recently tested)
- Strapi v4.x.x

(This package may work with older Strapi versions, but these are not tested nor officially supported at this time.)

**We recommend always using the latest version of Strapi to start your new projects**.

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

## 🔗 Links

- [NPM package](https://www.npmjs.com/package/strapi-code-themes)
- [GitHub repository](https://github.com/boazpoolman/strapi-code-themes)

## 🌎 Community support

- For general help using Strapi, please refer to [the official Strapi documentation](https://strapi.io/documentation/).
- You can contact me on the Strapi Discord [channel](https://discord.strapi.io/).

## 📝 Resources

- [MIT License](LICENSE.md)
