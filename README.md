# AFCP
AFCP, Arabic Font for Common Phrases, is a set of CSS rules that provide common phrases for Arabic language. You can customize colors, rotatation, size, and any powerful CSS delaration.

### Setting up AFCP in your project:
#### Simplest way:
Just add your following code into your `<head>` element:
```HTML
<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/amughrabi/afcp/master/bin/afcp-v1.min.css"/>
```

#### Simple way:
You can download AFCP as a zip file, and add it as a part of your project, for example:
Place all fonts from the dwonloaded zip file into your project `/fonts/` dirctory, and place the `afcp.css` file into your proper directory (anywhere in your webapp directory), then open the `afcp.css` and change `@font-face` font paths there:

```CSS
@font-face {
    font-family:"AFCP";
    src:url("${FONT_PATH}/AGA_Islamic_Phrases.eot?") format("eot"),
    url("${FONT_PATH}/AGA_Islamic_Phrases.woff") format("woff"),
    url("${FONT_PATH}/AGA_Islamic_Phrases.ttf") format("truetype"),
    url("${FONT_PATH}/AGA_Islamic_Phrases.svg#AGAIslamicPhrases") format("svg");
    font-weight:normal;
    font-style:normal;
}
```

Finally, you need to include the edited `afcp.css` into your project `<head>` element:

```HTML
<link rel="stylesheet" type="text/css" href="${AFCP_PATH}/afcp.css"/>
```

### Table of Arabic Common Phrases:

We are using [font2u.com](http://www.fonts2u.com/aga-islamic-phrases.font) font that available us to draw more than 90 common arabic phrases, and these phrases are listed as bellow:

[![font2u.com](http://i.fonts2u.com/ag/mp1_aga-islamic-phrases_1.png)](http://www.fonts2u.com/aga-islamic-phrases.font)

This font is for **personal use**.

### Functional Demo
<p data-height="268" data-theme-id="0" data-slug-hash="pjBaOw" data-default-tab="result" data-user="amughrabi" class='codepen'>See the Pen <a href='http://codepen.io/amughrabi/pen/pjBaOw/'>Arabic Font for Common Phrases - AFCP</a> by Ahmad AlMughrabi (<a href='http://codepen.io/amughrabi'>@amughrabi</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
