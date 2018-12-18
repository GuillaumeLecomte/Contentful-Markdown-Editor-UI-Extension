# Contentful-Markdown-Editor-UI-Extension
Small Markdown Editor as Contentful UI Extension


## [SimpleMDE](https://github.com/sparksuite/simplemde-markdown-editor "SimpleMDE") as Markdown Editor
Easy to integrate and customize. I added a Save button which triggers Contentful SDK SaveValue-Function. 
Plus, a small Vue component uses [Showdown](https://github.com/showdownjs/showdown "Showdown MD to HTML Converter") for converting MD to HTML.

In this editor you insert keys from [Phraseapp](https://phraseapp.com/ "Phraseapp.com") Localisation tool which then later will be replaced by the actual translation by a backend. For both Use Cases, I want translated MD and I want translated HTML, it is easier to have both MD and HTML in Contentful as single source of truth.

![Contentful Phraseapp UI Extension](https://raw.githubusercontent.com/TinkeringAround/Contentful-Markdown-Editor-UI-Extension/master/images/Contentful-Markdown-Editor-Extension.PNG "Contentful Markdown Editor UI Extension")

## Setup
![Contentful Phraseapp UI Extension](https://raw.githubusercontent.com/TinkeringAround/Contentful-Markdown-Editor-UI-Extension/master/images/Setup.PNG "Contentful Markdown Editor UI Extension")


## Contentful SDK
Check out [Contentful UI Extension SDK](https://github.com/contentful/ui-extensions-sdk "Contentful UI Extension SDK") for more Information of building a Contentful UI Extension on your own and 
[Check out their GitHub Page](https://github.com/contentful/contentful.js).
