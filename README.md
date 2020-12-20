# 🔗 URL Shortener for Warga Tiga

This is Warga Tiga's URL shortener from [nelsontky's Github Page shortener](https://github.com/nelsontky/gh-pages-url-shortener/ "nelsontky's Github Page shortener").

## 👨‍🏫 Demo

1. [url.wargati.ga/1](https://url.wargati.ga/1) should link to this repo.

1. To add a new short link, add an issue with the title being the link you want
   to shorten (including the `http(s)://`) to
   [https://github.com/farellfaiz/wargatiga-url-shortener/issues](https://github.com/farellfaiz/wargatiga-url-shortener/issues).

1. The newly created short url can be accessed via `url.wargati.ga/{issue_number}`

## ☕️ Features

1. Unlike many URL shorteners, this one ~~does not need a database~~ uses a
   "database" in the form of GitHub issues and can be entirely hosted on GitHub
   pages.

1. There is no need for the pound symbol - short URLs look clean like this:
   `url.wargati.ga/1` instead of looking like this: `url.wargati.ga/#1`.

## 💡 How does this work?

_Thanks to @kidGodzilla for the pretty neat explanation
[here](https://github.com/nelsontky/gh-pages-url-shortener/issues/5#issuecomment-728040879)._

> 1. 404.html handles all requests
> 1. Small javascript snippet fetches a JSON representation of the GitHub issue
>    via the JSON API, and redirects to the issue title, as a URL.
> 1. Profit?

## 👨‍💻 Credit
- [Farell Faiz](https://github.com/farellfaiz "Farell Faiz")
- [nelsontky](https://github.com/nelsontky "nelsontky")