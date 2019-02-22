# Tailwind CSS Webpack Starter Project

A Tailwind CSS Starter. Based on Tailwind CSS, Webpack, PostCSS, cssnano and purgecss. Fully optimized for top performance.

- [Tailwind CSS](https://tailwindcss.com) - The Utility-First CSS Framework. A project by Adam Wathan (@adamwathan), Jonathan Reinink (@reinink), David Hemphill (@davidhemphill) and Steve Schoger (@steveschoger).
- [Webpack](https://webpack.js.org/)
- [PostCSS](https://postcss.org/)
- [cssnano](https://cssnano.co/)
- [Purgecss](https://www.purgecss.com)

To get started, clone the project and install the dependencies:

```
# Using npm
npm install
```

After that, start up Webpack Development Server:

```
npm run dev
```

The page is rendered here <http://localhost:8080/>.

Webpack Development Server will watch `/src/styles.css` and `/tailwind.js` and rebuild your stylesheet on every change. You can play around with `/src/index.html` to see the effects of your changes.

The sample page renders [my blog](https://blog.anibalhsanchez.com) layout redesigned with Tailwind ;-)

To build a production bundle run:

```
npm run prod
```

After that you will have a ready to deploy bundle at `/dist`

## Contributing

Have a lot of experience with Webpack and suggestions on how we could improve this starter template? We'd love a PR!

This starter is based on the original project created by Adam Wathan here: <https://github.com/tailwindcss/webpack-starter>.

## Copyright & License

- Copyright (c)2007-2018 Extly, CB. All rights reserved.
- Distributed under the GNU General Public License version 3 or later; see LICENSE
- This project is dedicated to [Andrea Gentil](http://www.twitter.com/andreagentil) ;-D
