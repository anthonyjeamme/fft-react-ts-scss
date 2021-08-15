# FAST-FILES TEMPLATE

Fast-files is a vscode extension to help developer generating files faster.

## Installation

1. install the vscode extension `anthonyjeamme.fast-files`
2. install the cli tool `npm i fast-files-cli -g`
3. in your project root, initialize fast-files with `fast-files init`
4. in your project root, type `fast-files import anthonyjeamme fft-react-ts-scss`

Then you can generate files wherever you want by right clicking on folder where you want to generate files.

Click `Generate files from template`, then select the template your want. Gatz, your files are generated !

## Set default template

To set default template, set in your configuration file the folowing prop : 

```json
{
    "fast-files":{
        "default-template": "react-component"
    }
}
```
