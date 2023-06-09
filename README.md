# CKEditor 5 editor advanced build

This build includes the following modules: Autoformat, Block quote, Bold, Link, Indent, Italic, List, Media embed, Paste from Office, Table, Table toolbar, Text transformation, Base64 upload adapter, Code blocks, Image, Image resize, Image style, Image toolbar, Image upload.

### Installation

In order to rebuild the application you need to install all dependencies first. To do it, open the terminal in the project directory and type:

```
npm install
```

Make sure that you have the `node` and `npm` installed first. If not, then follow the instructions on the [Node.js documentation page](https://nodejs.org/en/).

### Adding or removing plugins

Now you can install additional plugin in the build. Just follow the [Adding a plugin to an editor tutorial](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/installing-plugins.html#adding-a-plugin-to-an-editor)

### Rebuilding editor

If you have already done the [Installation](#installation) and [Adding or removing plugins](#adding-or-removing-plugins) steps, you're ready to rebuild the editor by running the following command:

```
npm run build
```

This will build the CKEditor 5 to the `build` directory. You can open your browser and you should be able to see the changes you've made in the code. If not, then try to refresh also the browser cache by typing `Ctrl + R` or `Cmd + R` depending on your system.

## What's next?

Follow the guides available on https://ckeditor.com/docs/ckeditor5/latest/framework/index.html and enjoy the document editing.

## FAQ
| Where is the place to report bugs and feature requests?

You can create an issue on https://github.com/ckeditor/ckeditor5/issues including the build id - `ya1bt6eydqv4-consog53htr3`. Make sure that the question / problem is unique, please look for a possibly asked questions in the search box. Duplicates will be closed.

| Where can I learn more about the CKEditor 5 framework?

Here: https://ckeditor.com/docs/ckeditor5/latest/framework/

| Is it possible to use online builder with common frameworks like React, Vue or Angular?

Not yet, but it these integrations will be available at some point in the future.
