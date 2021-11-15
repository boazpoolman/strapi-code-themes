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
