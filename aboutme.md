---
layout: page
title: About this site
subtitle:
---

This site can be used as a template for collections of JClic projects hosted on GitHub pages.

The site is automatically generated and updated by [Jekyll](https://jekyllrb.com/) on [GitHub pages](https://pages.github.com/). It can also be manually generated and uploaded wherever you want.

_JClic collections_ is based on Dean Attall's [Beautiful Jekyll](http://deanattali.com/beautiful-jekyll/).

## How to create your JClic collection
- First of all, you will need an account on [GitHub](https://github.com). Choose a significant user name, because it will be an important part in the final URL of your site.
- Log-in into GitHub.com with your newly created account and go to: [https://github.com/silaiu/silaiu.github.io](https://github.com/silaiu/silaiu.github.io)
- Fork this repository (press the __Fork__ button, at top right)
- Go to the __Settings__ tab of your new repository and rename it to:<br>
**_yourgithubusername_.github.io**<br>
(where, of course, _yourgithubusername_ is YOUR GitHub user name)
- Edit the file named `_config.yml`, changing all references to "silaiu" with your GitHub user name. You must also change the title, description, usernames on social networks, etc.
- Save the changes (you will be asked for a short comment) and your site will be available on: **https://_yourgithubusername_.github.io**

## How to add packages to the collection
- Go to the `projects` folder of your repository and click on __Add files__.
- Drop here the folder obtained when exporting the project to HTML5 with [JClicAuthor](https://clic.xtec.cat/en/jclic/download.htm). - Write a brief description (for example: "adding project xxx") and commit the changes.
- Go to the `_posts` folder and create a new file. The name of the file must follow the same pattern of the existing samples, like:<br>
`yyy-mm-dd-title-of-the-project.md`
- Edit this file and fill it with this content:

```yaml
---
layout: jclic-project
title: Title of your new project
subtitle: Subtitle of your project (leave it blank if not needed)
project: projectfoldername
thumb: project-thumb.jpg
---
Long description of the project....
```

Commit all changes and see the result on https://_yourgithubusername_.github.io

