---
layout: default
title: Create GitHub account
nav_exclude: true
---

 [How to create a GitHub Pages site?](#how-to-create-a-github-pages-site)  
 [How to run a GitHub Pages site from another repository?](#how-to-run-a-github-pages-site-from-another-repository)


# How to create a GitHub Pages site?
GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub and publishes a website. GitHub Pages publishes any static files that you push to your repository. You can create your own static files or use a static site generator, e.g. **Jekyll**. It takes Markdown and HTML files and creates a complete static website. Jekyll supports Markdown and Liquid, a templating language that loads dynamic content on the site.

1. Create a new repository.
2. Name the new repository according to the following scheme  
   ```
   username.github.io.  
   ```
   ![Image](/github_pages_1.png "github_pages_1")  
3. Set visibility to **Public**.  
   ![Image](/github_pages_2.png "github_pages_2")  
4. Click **Add a README file** checkbox, if you wish.
5. Click on **Create repository**.
6. Next, fork repository from pmarsceill/just-the-docs. It's a modern, high customizable, responsive Jekyll theme for documention with built-in search.  
   ![Image](/github_pages_3.png "github_pages_3")  
7. From repository just-the-docs, forked to your account, copy some files: **_config.yml** and **index.md** and add them to your new repo.
8. Using any code editor, custom the content of the files according to your requirements. The files are created as templates and they can be easily adapted to the needs of the current project. The files contain some instructions how to work out them.
9. **_config.yml** file is the main configuration file for Jekyll and must contain a line like this:  
remote_theme: pmarsceill/just-the-docs
10. Now, develop the content of other pages as **.md** documents, according to the needs of the project and rules of **Jekyl**.
11. Upload everything to your GitHub using GitHub Desktop. On the viewed site, just-the-docs automatically generate left navigation panel and enable the built-in search. You can customize it any way you like. For more information, refer to the [documentation](https://docs.github.com/en/github/working-with-github-pages).


# How to run a GitHub Pages site from another repository?  
*According to Magdalena Niedźwiecka-Pruszkowska*


Typically, a static page could be hosted on GitHub at:

```
https://username.github.io
```

Magda found that the page can be hosted from any repository, after the character like:
```
/
```
For example 
```
https://username.github.io/yourrepo
```

1. Go to the public repository to be used for the static page.
2. Click on **Settings**.
3. Go down to GitHub pages.
4. Change the settings: from **none** to **master** (or **main**, depending on what you have) or to any branch to put the page in.
5. Save the settings.
6. Go back to the main repository page (Code < >).
7. On the right side is **Environments** section - GitHub pages should be marked as **Active**
8. Click on **Environments** and it takes you to the **Deployments**/acitvity log page
9.  Click on **View deployment**
10. You've got the GitHub Pages site from another repository!

[Back](./git_github_and_github_desktop.md)