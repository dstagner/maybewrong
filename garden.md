---
title: garden
---

When I started using Obsidian, it was great for developing my ideas and sharpening my thoughts. But it got me wanting to try once again to create a public site. This led me to the idea of a digital garden, and how others have adapted Obsidian's Markdown flexibility to create websites that reflect how we actually think. 

### Who is this for?
This plan assumes you are comfortable with the basic tools of programming, or at least willing to climb some pretty steep learning curves. If you're not a programmer, and just want to get a digital garden going with Obsidian, I'd strongly recommend just using [Obsidian Publish](https://obsidian.md/publish). Yes, it costs money, but your time is worth more than your money. 

## Using gitmodules to separate Obsidian and Jekyll

### Creating the submodule
```
git submodule add -b [branch] [URL] [DirectoryName]
```

### Custom build script
subbuild.sh

### Triggering Netlify builds from submodule changes
Flavio Copes documented [this method for triggering Netlify builds from git submodule commits](https://flaviocopes.com/netlify-deploy-git-submodule-github-actions/). 

Current headache: getting Netflify to run git submodule update --remote

### Using iCloud with git
