# contribution


First go please to the Internal Developer Platform [idp.softreck.dev](http://idp.softreck.dev)

[Contribution information for projects development](https://github.com/softreck/contribution)

Contribution information for projects development

+ [CHANGELOG.md](/CHANGELOG)
+ [CODE_OF_CONDUCT.md](/CODE_OF_CONDUCT)
+ [CONTRIBUTING.md](/CONTRIBUTING)
+ [GOVERNANCE.md](/GOVERNANCE)
+ [LICENSE](/LICENSE)


## Tools for markdown

[showdownjs/showdown: A bidirectional Markdown to HTML to Markdown converter written in Javascript](https://github.com/showdownjs/showdown)


[Getting Started | Eleventy, a simpler static site generator.](https://www.11ty.dev/docs/getting-started/)


## Start project 
Let’s create it with npm init. 
The -y parameter tells npm to skip all the questions and just use the defaults.

    npm init -y


## 11ty

install and save Eleventy into our project’s package.json by running:

    npm install --save-dev @11ty/eleventy

run Eleventy 

    npx @11ty/eleventy

serve

    npx @11ty/eleventy --serve


### 5. Run Eleventy

```
npx eleventy
```

Or build and host locally for local development
```
npx eleventy --serve
```

Or build automatically when a template changes:
```
npx eleventy --watch
```

Or in debug mode:
```
DEBUG=* npx eleventy
```
