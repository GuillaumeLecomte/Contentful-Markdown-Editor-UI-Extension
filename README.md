# Contentful-Markdown-Editor-UI-Extension
Small Markdown Editor as Contentful UI Extension


## [SimpleMDE](https://github.com/sparksuite/simplemde-markdown-editor "SimpleMDE") as Markdown Editor
Easy to integrate and customize. I added a Save button which triggers Contentful SDK SaveValue-Function. 
Plus, a small Vue component uses [Showdown](https://github.com/showdownjs/showdown "Showdown MD to HTML Converter") for converting MD to HTML.

In this editor you insert keys from [Phraseapp](https://phraseapp.com/ "Phraseapp.com") Localisation tool which then later will be replaced by the actual translation by a backend. For both Use Cases, I want translated MD and translated HTML, it is easier to have both MD and HTML in Contentful as single source of truth.

![Contentful Phraseapp UI Extension](https://raw.githubusercontent.com/TinkeringAround/Contentful-Markdown-Editor-UI-Extension/master/images/Contentful-Markdown-Editor-Extension.PNG "Contentful Markdown Editor UI Extension")



## :rocket: Dependencies & Installation
Node & NPM

Just copy the *index.html* file into the Code Block in Contentful Web-App or use Contentful CLI.

![Contentful Phraseapp UI Extension](https://raw.githubusercontent.com/TinkeringAround/Contentful-Markdown-Editor-UI-Extension/master/images/Setup.PNG "Contentful Markdown Editor UI Extension")

Alternativly, you can use the script to create, deploy/update and delete the extension.




## :star: Configuration
Edit config attribute in package.json to insert your Contentful Space ID and the name and field type of the UI extension.

## :cloud: Available Scripts
In the project directory, you can run:

### `npm login`
Fetches a Contenful management token after login via browser UI. This token will be stored and used for further requests.

### `npm create`
Initial setup of a UI extension.

### `npm run deploy`
Updating the existing UI extension.
Throws an error if the extension has not been created by `npm create` or via Contentful Web UI.

### `npm run delete`
Deleta a existing UI extension.
Throws an error if the extension has not been created by `npm create` or via Contentful Web UI.


## Contentful SDK
Check out [Contentful UI Extension SDK](https://github.com/contentful/ui-extensions-sdk "Contentful UI Extension SDK") for more Information of building a Contentful UI Extension on your own and 
[Check out their GitHub Page](https://github.com/contentful/contentful.js).
