# 💌 Simple Wedding Invitation Website Template

![Thumbnail](/assets/images/banner.webp)

[![Netlify Status](https://api.netlify.com/api/v1/badges/cef32dbf-f26f-4865-84a9-b85a439c9994/deploy-status)](https://app.netlify.com/sites/ulems/deploys)
[![Hits](https://dikit.my.id/0b3y8q)](https://cie.my.id)
[![GitHub repo size](https://img.shields.io/github/repo-size/dewanakl/undangan?color=brightgreen)](https://shields.io)
[![GitHub License](https://img.shields.io/github/license/dewanakl/undangan?color=brightgreen)](https://shields.io)

## 🚀 Demo
For those who want to see the demo first:

[https://ulems.my.id/?to=Friends](https://ulems.my.id/?to=Friends)

## 📦 Documentation

* Run the command `npm install`, then `npm run dev`, and open `http://localhost:8080`.
* Change the contents of the `index.html` file as desired.
* If you don't want to use the **comment feature**, remove the `data-url` and `data-key` attributes from the `<body>` element in index.html.
* Adjust the `data-url` on the `<body>` in index and dashboard according to your backend URL (if you're hosting it yourself).
* Also adjust the `data-key` in the index with the access key that you can get from the dashboard.
* If you want to use GIF, get the Tenor API key at [developers.google.com/tenor](https://developers.google.com/tenor/guides/quickstart).
* For deployment, run `npm run build:public`. The `public` folder is what you'll upload.
* For self-hosted backend, see the explanation below, or use the **trial API** for free.

> This invitation only uses regular HTML, CSS, and JavaScript. NPM is used so that JavaScript files can be executed directly (not as a module type anymore).

> If you still want to use without NPM, change `src="./dist/guest.js"` to `src="./js/guest.js" type="module"` in the `<head>` tag in index and dashboard.html, with the risk of theme glitches at the beginning of loading.

> If you have questions, use the `discussions` feature so it can also be read by others.

> [!WARNING]  
> Use version 3.14.0, version 4 is still in development and has the potential for bugs 🐛

## 🔥 API Deployment

- Video\
    Coming soon

- Presentation
    [https://docs.google.com/presentation](https://docs.google.com/presentation/d/1EY2YmWdZUI7ASoo0f2wvU7ec_Yt0uZanYa8YLbfNysk/edit)

## ⏰ Trial API
For those who want to try it for free:

[https://trial.ulems.my.id](https://trial.ulems.my.id)

## ⚙️ Tech stack

- Bootstrap 5.3.8
- AOS 2.3.4
- Fontawesome 7.1.0
- Canvas Confetti 1.9.3
- Google Fonts
- Vanilla JS

## 🎨 Credit
All visual assets in this project are sourced from Pixabay.

## 🤝 Contributing

I'm very open to those of you who want to contribute to this invitation template!

## 🐞 Security Vulnerabilities

If you find any security vulnerabilities in this project, please email DKL via [dewanakretarta29@gmail.com](mailto:dewanakretarta29@gmail.com).

## 📜 License

This invitation template is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
