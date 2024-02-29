# dmenu-websearch

Shorthand for web search based on each own query with dmenu.

## 📦 Dependencies

0. [dmenu](https://tools.suckless.org/dmenu), is a dynamic menu for X
1. [jq](https://github.com/stedolan/jq), is a lightweight and flexible command-line JSON processor

## 🌎 Web Search Queries

`urlquery`

```
DuckDuckGo:Search,https://duckduckgo.com/?q=
GitHub:Search,https://github.com/search?q=
Google:Search,https://duckduckgo.com/?q=!g+
Google:Search:Image,https://duckduckgo.com/?q=!gi+
Google:Translate_to_PL,https://translate.google.com/?sl=auto&tl=pl&text=
Wikipedia:EN,https://en.wikipedia.org/w/index.php?search=
Wikipedia:PL,https://pl.wikipedia.org/w/index.php?search=
```

## 🏗️ How to add new query?

Just open the url file and add the new line with `<keyword>,<url_query>` syntax.

## 🍱 How to use?

Call `dmenu-websearch`. Choose your prefix menu, or you able to complete the **perfix menu** with <kbd>Tab</kbd>, and write down your keywords.

The form should be like this,

```
Arch:Packages libreoffice still
^^^^^^^^^^^^^ ^^^^^^^^^^^^^^^^^
 prefix menu      keywords
```

**TIP**: You're free to define the **prefix menu**. My example is just for ease to explaining.
