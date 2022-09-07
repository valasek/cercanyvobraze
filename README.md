# Čerčany v obraze

Stránky jsou hostovány na [Netlify](https://app.netlify.com/sites/cercanyvobraze/overview). Psané v statickem generátoru stránek [Hugo](https://gohugo.io/) a používají tému [WowChemy]((https://github.com/wowchemy/starter-hugo-academic)).

Theme can be customized by duplicating files from this repo: https://github.com/wowchemy/wowchemy-hugo-themes/tree/main/modules/wowchemy

- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- ⬇️ **Automatically import your publications from BibTeX** with the [Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli)
- 💡 [Suggest an improvement](https://github.com/wowchemy/wowchemy-hugo-themes/issues)
- ⬆️ **Updating?** View the [Update Guide](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-themes/releases)

---
## Poznámky pro aktualizaci

Lokální spuštění možné pomocí příkazu

```
hugo server
```

V případe chyby typu 
```
Error: Error building site: "...": failed to extract shortcode: template for shortcode "..." not found
```

```
hugo mod clean
hugo mod get -u ./...
```

---
Původní změny ještě byli v:
- layouts/_default/baseof.html
- layouts/partials/page_metadata.html