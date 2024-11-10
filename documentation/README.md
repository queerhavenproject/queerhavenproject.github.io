# README

This is a Hugo website based on the theme [Ananke](https://github.com/theNewDynamic/gohugo-theme-ananke)

To update this website edit the markdown files in content/. Images should be placed in static/images/ and can be accessed by the markdown files with the correct path. See [content/en/Learning/chapter-1.md] for an example. 

More pages can be added by copying existing markdown files into the directories, and modifying the new files with the new content. Add tags in the meta data headers for links between articles. 

Basic customization is possible by editing config.toml or the headers on each markdown file with parameter tags for that specific page. More customization is possible through the custom.css file for experts. 

This website is built and deployed live by Github Actions, changes to the main branch will trigger a new build to deploy. 