Installation and Configuration Guide

1. Preparation

Before you begin, make sure you have the following dependencies installed:

Git: A version control system to manage your codebase.
Hugo: The static site generator for building your site.
Text Editor: A code editor for editing your files (e.g., VS Code or Sublime Text).

2. Theme Setup and Basic Structure
   Choose a Theme:

Select a Hugo theme that suits your project needs. You can browse available themes at Hugo Themes.
Apply the Theme:
Once you have chosen a theme, apply it by editing the config.toml or config.yaml file. For example, add the following settings:

Header:
Define the title and description for your blog.

Example:
title = "My Hugo Blog"
description = "A personal blog showcasing my projects and thoughts."
Footer:
Add copyright information and social media links.

Example:
copyright = "© 2025 My Name"
[social]
twitter = "https://twitter.com/username"
github = "https://github.com/username"
About Page:
Create a brief profile of yourself (e.g., as a student). You can create this as a page and link it in the menu.

Example:
hugo new about.md
Then, edit the about.md file to add a short bio.

3. Run and Publish the Blog
   Run Hugo Locally:
   To preview your site locally, run the following command in your project directory:

hugo server
Your site will be available at http://localhost:1313.

Publish the Blog:
After making sure everything works as expected, it's time to publish your blog. You can deploy your blog using platforms like GitHub Pages, Netlify, or others. Here's how you can do it using GitHub Pages:

Push Your Project to GitHub:
First, create a repository on GitHub and push your Hugo project there.

git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/your-repo.git
git push -u origin master
Configure GitHub Pages:
Set up GitHub Pages by navigating to the repository settings, then choose the gh-pages branch as the source for your site.

Deploy to Other Platforms (Optional):
You can also deploy your site to Netlify, Vercel, or other hosting services by following their deployment guides.

4. Publication Links
   Once your site is live, you can share the following links:

🖥 Live Blog: https://mhmdrobeth.github.io/
📂 GitHub Repository: https://github.com/mhmdrobeth/mhmdrobeth.github.io
