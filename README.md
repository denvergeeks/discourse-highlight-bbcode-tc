### A Discourse Theme Component that adds a button in the Composer Toolbar you can use to highlight, and also color selected text in Posts.

Based on https://github.com/merefield/discourse-tc-coloured-text

Difference is this one defaults to highlighting with a yellow background (in case you want the simplicity of that), but is changeable while editing the text because it's just simply inserting bbcode to let youset the hex code for text color and background.

i.e. Inserts this bbcode wrapper...

```[wrap=color color=# bgcolor=#ff8]wraps this selected text with a yellow background[/wrap]```

to output this on the saved page or post...

![Screenshot 2023-09-03 053252](https://github.com/denvergeeks/discourse-highlight-bbcode-tc/assets/322529/2205cf8a-5436-49f2-bf00-4b8fba933d19)

### If you only want a dead simple highlighter in the Discourse Composer Toolbar, you can also see my other plugin, Highlighting Composer Button for Discourse:

https://github.com/denvergeeks/discourse-highlight-wrap-theme-component

