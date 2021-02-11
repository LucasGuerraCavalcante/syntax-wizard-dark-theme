# Syntax Wizard Theme

### VS Code Dark Theme inspired by GitHub's VS Code dark theme, magic, wizards and heavy metal.
😄 💜 🧙 🔮

## Previews


|   |   | 
| ------------- | ------------- | 
|  JavaScript |  Json | 
| ![JavaScript](https://i.imgur.com/gTH41vI.png)  | ![json](https://i.imgur.com/5ZPeNkv.png)  |
|  HTML | CSS  | 
| ![HTML](https://i.imgur.com/ekyoHDz.png)  | ![CSS](https://i.imgur.com/LXVlbqL.png)  |
| Python  | C++  | 
| ![Python](https://i.imgur.com/gIN2Z2H.png)  | ![C++](https://i.imgur.com/0qFj3xJ.png)  |


## Background 

This is a very personal small project. 

Since I've never found a theme that was completely visually pleasing to me, I was determined to try to find some balance by editing a theme that already existed.

My problem with some themes is my dislike for some specific colors (which is completely subjective). I particularly hate yellow and orange, which are unfortunately very common for representing strings. I don't like white either, I don't know why but it sometimes feels "out of context" to me. Also, I think that a dark theme should have a really dark background, something close to black feels more pleasing to me.

And I 💜 purple on dark backgrounds.

So guided by these subjective personal tastes that no one cares about, I started it...

## Inspirations 

I felt in love with the GitHub syntax highlight theme, especially the dark one. So I've decided to edit GitHub's VS Code theme, available here [github.com/primer/github-vscode-theme](https://github.com/primer/github-vscode-theme).

About the name... Well, it now has a lot of purple, which sometimes is related to magic and wizards, especially in video games and pop culture. It also reminds me of Electric Wizard, a heavy metal band that often uses purple in their artworks. So I came up with the Syntax Wizard 🧙🔮 . If there is a Dracula, I not a Wizard?! 😄

# More Stuff

## If you want to edit this theme, contribute to it or even make your own

```bash
git clone https://github.com/LucasGuerraCavalcante/syntax-wizard-dark-theme.git
```

Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (macOS) to see a list of Markdown snippets

### For more information
* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

## What's in the folder

* This folder contains all of the files necessary for your color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/LucasGuerraCavalcante-color-theme.json` - the color theme definition file.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Inspect TM Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) .

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

## Make your on VS Code theme

```bash 
npm install -g yo generator-code
```

```bash 
yo code
```

* Really useful content [here](https://livierickson.com/blog/create-your-own-color-theme-for-visual-studio-code/)!!!!

## License

LucasGuerraCavalcante/syntax-wizard-dark-theme is licensed under the MIT License.

