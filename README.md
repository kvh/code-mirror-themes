CodeMirror Themes
=================

Code Mirror is a great online editor, however, it's lacking some good themes. So, here are a crap ton for your coding pleasure.

I used this <a href="https://github.com/FarhadG/codeMirror-aceEditor-theme-generator" target="_blank">theme generator</a> to export themes from editors like Sublime Text, Ace Editor and TextMate. There's also a link in the generator to a visual interface where you can edit a theme live and then rn the generator script over the file to have it converted to CodeMirror.

A few modifications were made to the base styling to make the default theme look better; e.g. line-heights, fonts, etc. Some version have a default version (source CodeMirror) included as well.

If something is not working or you would like a new feature, please use the issues page.


## Installation

You can simply fork and clone (or download) the repo into your local directory and check out the themes folder for the CSS files.

```
  $ git clone https://github.com/FarhadG/codeMirror-themes
  $ cd codeMirror-themes/themes
```


## Usage

Once you have the desired CSS file, you simply configure your CodeMirror editor and pass in the theme's name as the CodeMirror theme name (use lowercase and spaces are treated with hyphens). For example, here's a simple configuration.

```
    // Theme Name: Bespin
    var myCodeMirror = CodeMirror(document.body, {
        mode: 'javascript',
        lineNumbers: true,
        theme: 'bespin'
    });

    // Theme Name: All Hallow Eve
    var myCodeMirror = CodeMirror(document.body, {
        mode: 'javascript',
        lineNumbers: true,
        theme: 'all-hallow-eve'
    });
```


## Demo

Here's a theme I extracted from one of my favorite Sublime Themes (itg-flat). I had to add an additional 4-5 CSS selectors to get it nearly there.

<img style='width: 100%' src='http://i58.tinypic.com/28vrkt1.png' />


## GUI Interface

Also, here's a <a href="http://tmtheme-editor.herokuapp.com/" target="_blank">LINK</a> for making SublimeText and TextMate with a visual interface. After saving the file, you can, then, take the file and run this <a href="https://github.com/FarhadG/codeMirror-aceEditor-theme-generator" target="_blank">theme generator</a> for converting the XML to CSS.


## Options

I'll be adding more features; that said, if you'd like a feature, let me know so that I'll try and implement it into future updates.
