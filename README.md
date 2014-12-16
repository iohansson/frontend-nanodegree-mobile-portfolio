I'm not sure what I have to include in that readme file.

To run an application clone the repository, then just open index.html

What I've done to optimize site performance:

<ul>
  <li>Minified and inlined style.css in all html pages. I think it is not a good solution, because if I'll want to change something common I'll have to do a lot of work. But requirement said to achieve PageSpeed Insights score. So.</li>
  <li>Fixed performance issues in main.js used in pizza project. It now performs well.</li>
  <li>Minified all javascripts</li>
  <li>Moved inline script to a file and made it async. It connects analytics, so no need for it to block the parser</li>
  <li>Optimized images using different JPEG and PNG optimization online tools</li>
  <li>For css that's in separate files used media queries in links</li>
</ul>

I think that's all. All pages get a good score on PageSpeed. All of them look good. That's why I think I've done the project.