# project-website-template

__A website template for your final project__ 🔮

By using this template you would be able to create your own website and deploy it on Github Pages. This project creates a static website, to test it locally (on your machine) you need to install [Hugo](https://gohugo.io/getting-started/installing/). This facilitates you to develop it and display the changes in real-time.

Therefore, you can click on the [***Use this template***](https://github.com/peterampazzo/project-website-template/generate) button 😉

#### [DEMO](https://peterampazzo.github.io/project-website-template/)

## How to

### Develop

If you managed to install Hugo on your machine, and cloned the repo, you can run `hugo serve`. At this point, you can surf your website from a browser at: [http://localhost:1313/](http://localhost:1313/).

When you commit changes to the main branch, a job (which runs using Github Actions) will build a new copy of your website and publish it on Github Actions. You might need to check the repo settings (under the 'Pages' tab). 

### Add new content

In the `content/` folder you can find several markdown files. `_index.md` would be your homepage. Therefore, you are free to create new markdown files. You need to make sure to include these fields in the beginning of your file:

```markdown
---
title: Page title
prev: link-prev-page
next: link-next page
---
```

Whereas, `prev` and `next` are the link to the pages displayed at the bottom of the page. If omitted, no link is going to be displayed!

Please, check the examples provided and the source code. By using Markdown you will be able to include:

* Formatted text (bold, italic)
* Images
* Tables
* Math formula
* Code
* Quotes
* Lists

### Update `config.toml`

The [`config.toml`](https://github.com/peterampazzo/project-website-template/blob/main/config.toml) file contains many variables related to your project. Here you can update much information such as: Project title, Authors, Links, Navbar. The changes are propagated and displayed automatically on every page you've created.

Make sure to update the `baseUrl` variable!


### Assets 

Images and other files can also make public together with the website. They must be stored in the `static/` folder. You may find already the DTU logo saved there. Also, you can export your Jupyter notebook and save it as an HTML file (`File > Export Notebook as > HTML`) and save it there. This way you can publish [your code](https://peterampazzo.github.io/project-website-template/explainer-notebook.html).

## Tech stuff 🤠

This template has been built on top of [Minimal Blog](https://github.com/tailwindtoolbox/Minimal-Blog) and wrapped into a [Hugo](https://gohugo.io/) website. 

Some of the technologies used are:
* [Hugo](https://gohugo.io/)
* [Tailwind CSS](https://tailwindcss.com/)
* [MathJax](https://www.mathjax.org/)
* [Feather Icons](https://feathericons.com/)
