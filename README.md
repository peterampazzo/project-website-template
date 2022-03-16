# project-website-template

By using this template you would be able to create your own website and deploy it on Github Pages. This project create a static website, to test it locally (on your machine) you need to install [Hugo](https://gohugo.io/getting-started/installing/). This facilitate you to develop it and display the changes in real time.

Therefore, you can click on 'Use this template' button 😉

#### [DEMO](https://peterampazzo.github.io/project-website-template/)

## How to

### Develop

If you managed to install Hugo on your machine, and cloned the repo, you can run `hugo serve`. At this point, you can surf your website from a browers at: [http://localhost:1313/](http://localhost:1313/).

When you commit changes to the main branch, a job (which runs using Github Actions) will build a new copy of your website and publish it on Github Actions. You might need to check the repo settings (under the 'Pages' tab). 

### Add new content

In the `content/` folder you can find several markdown files. `_index.md` would be your homepage. Therefore, you are free to create new markdown files. You need to make sure to include this fields in the beggining of your file:

```markdown
---
title: Page title
prev: link-prev-page
next: link-next page
---
```

Whereas, `prev` and `next` are the link to the pages displayed in the bottom of the page. If obmitted, no link is going to be displayed!

Please, check the examples provided and the source code. By using Markdown you will be able to include:

* Formatted text (bold, italic)
* Images
* Tables
* Math formula
* Code
* Quotes
* Lists

### Update `config.toml`

The [`config.toml`](https://github.com/peterampazzo/project-website-template/blob/main/config.toml) file contains many variables related to your project. Here you can update many information such as: Project title, Authors, Links, Navbar. The changes are propagated and displayed automatically to every pages you've created.
