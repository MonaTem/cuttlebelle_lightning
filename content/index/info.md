# Cuttlebelle
From their [site](https://cuttlebelle.com/) -
"Cuttlebelle is a static site generator that uses react for layouts, let’s you use one layout per page-partial and cleanly separates content from code."


## How to Install
```
$ npm install cuttlebelle --global
```
Create your directory and then run:
```
$ cuttlebelle init
```
To view your compiled static site with a live localhost, run:
```
$ cuttlebelle watch
```
After you edit your site, run this command in your directory to compile the html and css:
```
$ cuttlebelle
```
In your **site** directory the **index.html** will have all of the corresponding HTML
## Why use it?
Cuttlebelle allows you to template a static site using MD files for the content. React can be used in a wide variety of ways and this is just another way to think about how to use it. An MD file is a text file created using one of several possible dialects of the Markdown language.

Learn more about MD  [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
## What you need to know
Your ReactJS layout will be in the **page.js** in the **code** directory
The MD files for templating will be in **content** directory
Adding new MD files can be defined in the **index.yml**
### What's a .yml file?
[YAML](https://en.wikipedia.org/wiki/YAML) is a human-readable data serialization language. It is commonly used for configuration files, but could be used in many applications where data is being stored or transmitted.
### How to deploy on GitHub
In order to make use of the **index.html** file with GitHub pages, you'll need to init a repo in the **site** directory. If you make any changes, you'll need to run the **cuttlebelle** command in the root directory and then **git add./commit/push** in the **site** directory again.
