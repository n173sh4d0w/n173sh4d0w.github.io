---
layout: posts
title: Deploying Hexo Site
date: 2023-10-04 10:10:10
tags:
---

Are you ready to showcase your tech-savvy prowess to the world? Deploying your Hexo site on GitHub with a streamlined layout comprising Home, Blog, and Projects sections couldn't be simpler. Follow these concise, tech-centric steps, and you'll have your website up and running in no time!

**Step 1: Create a Hexo Site**

Before diving into deployment, you need to have a Hexo site ready to go. If you don't have one set up yet, don't fret! Hexo's easy-to-follow documentation will guide you through the process. Once your site is prepared, let's proceed.

**Step 2: Install the Cactus Classic Theme**

The Cactus Classic theme offers a clean and professional look, ideal for tech enthusiasts like yourself. Install it with a single command:

```shell
npm install hexo-theme-cactus-classic --save
```

**Step 3: Configure Your Hexo Site**

In your `_config.yml` file, make these swift adjustments:

```yaml
theme: hexo-theme-cactus-classic
deploy:
  type: git
  repository: https://github.com/YourGitHubUsername/YourGitHubUsername.github.io.git
  branch: master
```

Replace `YourGitHubUsername` with your GitHub username.

**Step 4: Organize Your Sections**

Create directories in your Hexo source directory for Home, Blog, and Projects sections. Keep it neat and structured!

**Step 5: Generate and Deploy**

Generate your site with `hexo generate`, and deploy it on GitHub Pages with `hexo deploy`. Your site is now live for the world to see!

**Step 6: Enjoy Your Site**

Your GitHub-hosted Hexo site, adorned with the elegant Cactus Classic theme, is now a reality. Showcase your tech prowess in style with Home, Blog, and Projects sections. Visitors can directly access your GitHub Projects, and your CV is just a click away!

With this simplified deployment process, your online presence has never been more impressive. Happy coding!
