# Ionic Pack for Visual Studio

[![Build status](https://ci.appveyor.com/api/projects/status/2ol794y2fuji0l9m?svg=true)](https://ci.appveyor.com/project/madskristensen/ionicpack)

Download this extension from the
[VS Gallery](https://visualstudiogallery.msdn.microsoft.com/d6279fba-bcff-4857-906d-29faa8a99448)
or get the
[nightly build](http://vsixgallery.com/extension/dcf84938-593b-49d8-9dff-d6014632e44e/).

-----------------------------------------

A set of tools to make you more productive working with
the Ionic Framework for Apache Cordova.

See the [changelog](CHANGELOG.md) for changes and roadmap.

**Note!** If you have ReSharper installed, you may
have to disable it to get any HTML Intellisense from
this extension.

## HTML

### Intellisense
It adds Intellisense for the Ionic directives in the HTML
editor.

![HTML Intellisense](art/html-intellisense.png)

Also attribute and attribute values have Intellisense.

![Attribute values](art/html-intellisense-attribute-values.png)

### Validation
The validation helps identify common mistakes and typos
directly in the editor, so you can quickly fix them
and move on.

![HTML Validation](art/html-validation.png)

### Snippets
Snippets makes it easy to scaffold markup components. They
appear in the regular HTML element Intellisenese and you
can easily identify them by their Ionic snippet icon.

![HTML snippets](art/html-snippets.png)

## JavaScript
When wring JavaScript, the edtiing is beefed up to
give even better and more precise Intellisense and tooltips
for projects consuming _ionic.bundle.js_

### Intellisense
Intellisense for JavaScript is also provided.

![JavaScript Intellisense](art/javascript-intellisense.png)

### Snipppets
Snippets makes it easy to scaffold scripted components. 
They appear in the regular JavaScript Intellisenese and
they all start with the word _ion_ followed by name.

![JavaScript snippets](art/javascript-snippets.png)

## Contribute
Check out the [contribution guidelines](./github/CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure
to install the
[Extensibility Tools 2015](https://visualstudiogallery.msdn.microsoft.com/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE)