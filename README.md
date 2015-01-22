To run an application you just can go to the [project page](http://iohansson.github.io/frontend-nanodegree-mobile-portfolio/) on GitHub Pages.

Or you can open it locally: clone the repository

`git clone https://github.com/iohansson/frontend-nanodegree-mobile-portfolio.git`

then go to folder where you've cloned the repository

`cd frontend-nanodegree-mobile-portfolio/`

and open `index.html` with your browser.

What I've done to optimize site performance:

- Minified and inlined style.css in all html pages. I think it is not a good solution, because if I'll want to change something common I'll have to do a lot of work. But requirement said to achieve PageSpeed Insights score. So.
- Fixed performance issues in main.js used in pizza project. It now performs well.
- Minified all javascripts
- Moved inline script to a file and made it async. It connects analytics, so no need for it to block the parser
- Optimized images using different JPEG and PNG optimization online tools
- For css that's in separate files used media queries in links

I think that's all. All pages get a good score on PageSpeed. All of them look good. That's why I think I've done the project.