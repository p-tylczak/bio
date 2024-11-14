# bio

Hosting on GitHub pages:
1. need to create a `.nojekyll` file at the root. Info here: https://github.blog/news-insights/the-library/bypassing-jekyll-on-github-pages/
2. need to add a config option in next.config.js to create appropriate prefix: `module.exports = { assetPrefix: '/bio/' }`.
   more info here: https://dev.to/jameswallis/deploying-a-next-js-app-to-github-pages-24pn
