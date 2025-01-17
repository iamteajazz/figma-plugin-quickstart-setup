# Figma Plugin Quickstart Setup

This repository provides a simple template to help developers quickly set up and start building their own Figma plugins. It includes a basic plugin structure, along with the necessary configuration files, so you can jump into development without unnecessary setup.


Below are the steps to get your plugin running. You can also find instructions at:

  https://www.figma.com/plugin-docs/plugin-quickstart-guide/

This plugin template uses Typescript and NPM, two standard tools in creating JavaScript applications.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Figma Desktop App](https://www.figma.com/downloads/)
- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/)
- [Figma Plugin Development Environment](https://www.figma.com/plugin-docs/)


 Node.js comes with NPM. This will allow you to install TypeScript and other
libraries. You can find the download link here:

  https://nodejs.org/en/download/

  ## Getting Started

Follow these steps to set up your local development environment and start working with the template:

 **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/figma-plugin-quickstart-setup.git
   cd figma-plugin-quickstart-setup


Next, install TypeScript using the command:

  npm install -g typescript

Finally, in the directory of your plugin, get the latest type definitions for the plugin API by running:

  npm install --save-dev @figma/plugin-typings

If you are familiar with JavaScript, TypeScript will look very familiar. In fact, valid JavaScript code
is already valid Typescript code.

TypeScript adds type annotations to variables. This allows code editors such as Visual Studio Code
to provide information about the Figma API while you are writing code, as well as help catch bugs
you previously didn't notice.

For more information, visit https://www.typescriptlang.org/

Using TypeScript requires a compiler to convert TypeScript (code.ts) into JavaScript (code.js)
for the browser to run.

Recommend writing TypeScript code using Visual Studio code:

1. Download Visual Studio Code if you haven't already: https://code.visualstudio.com/.
2. Open this directory in Visual Studio Code.
3. Compile TypeScript to JavaScript: Run the "Terminal > Run Build Task..." menu item,
    then select "npm: watch". You will have to do this again every time
    you reopen Visual Studio Code.

That's it! Visual Studio Code will regenerate the JavaScript file every time you save.
