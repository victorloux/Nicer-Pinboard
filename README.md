# Nicer Pinboard

This is an alternative stylesheet for [Pinboard](https://pinboard.in), which gives it a slightly more modern and usable look, while retaining the original simplicity that we all love.

- New font (Source Sans).
- Larger spacing and subtle separating lines between links, which makes the list much clearer and easier to browse
- Private links are now in yellow, and to-read links have an indicator
- Fixes the missing margin under `<blockquote>`s in link descriptions (that’s particularly useful if you use Pinboard Plus, which blockquotes selected text)
- A few other spacing and UI enhancements (in the details and tags)
- auto-adds flags next to language tags, if you save pages in several languages (e.g. `lang:fr`, `lang:de`). *(nb: you might want to comment this out if your browser/computer does not support Emojis.)*

## Installation

You will need the Stylish plugin, which is available [for Chrome](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe) and [for Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome). It’s like GreaseMonkey, but for CSS. This CSS should however work with similar extensions or methods if you are using another browser.


### Automatic installation

Install from UserStyles.org: https://userstyles.org/styles/118641/nicer-pinboard
You will have to edit the CSS once it's set up (click Stylish, then Edit) and add this line first:

```
@import url("https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,400italic,600");
```

### Manual installation

- Navigate to [pinboard.in](https://pinboard.in).
- Click the Stylish icon in your toolbar, then *Manage installed styles*, then *Write new style*.
- Copy the contents of `pinboard.css` in the Code section, and **make sure** that in the “Applies to” section, you then specify “URLs on the domain: `pinboard.in`”.
- Input a name and save.

## Screenshot

![Screenshot](screenshot.png)
