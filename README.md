# tulipsdev.github.io

Public pages for all tulipsdev apps, served with GitHub Pages at
https://tulipsdev.github.io/

One folder per app:

| Page | URL | Source |
|---|---|---|
| ShopLoop privacy policy | https://tulipsdev.github.io/shoploop/privacy/ | `privacy.*` keys in `ShopLoop/ShopLoop/Localizable.xcstrings` (shoploop-ios) |

Adding an app: create `<app>/privacy/index.html` and link it from `index.html`.

The ShopLoop page is generated from the app's string catalog so the web page and
the in-app Privacy page always say the same thing. When the in-app text changes,
regenerate the page and push.
