# Override CSS
![](https://img.shields.io/github/stars/tristanbudd/override-css.svg) ![](https://img.shields.io/github/forks/tristanbudd/override-css.svg) ![](https://img.shields.io/github/tag/tristanbudd/override-css.svg) ![](https://img.shields.io/github/release/tristanbudd/override-css.svg) ![](https://img.shields.io/github/issues/tristanbudd/override-css.svg)

## What is this for?
The Problem: CSS 3 (The Current Web Standard) has many default classes, you can see them all at [This Link](https://www.w3schools.com/cssref/css_default_values.php "This Link"). Alongside many useful features that are disabled by default / not configured, this file should help as a baseline for new projects to easily add custom styling without interference.

Some of the key issues with default CSS (Fixed with override.css):
- Inconsistent box sizing. (Exclude padding and borders when editing an elements width an height)
- Unexpected default margins and padding.
- Unwanted list styling.
- Forms behaving differently between browsers.
- Unnecessary table border spacing.
- Image, Video & IFrame overflowing containers.
- Mobile tap highlighting. (Overriding :hover, :focus and :active)
& Many more issues found and resolved.

## Installation
> [!NOTE]
> If you already have base css classes overwritten, you should remove them to avoid conflicts & unnecessary code (Ideally this is for new projects only).

1. Install the latest release: [Click Here](https://github.com/tristanbudd/override-css/releases/ "Click Here")
2. Place the override.css file under your root directory, public asset directory or anywhere where you can easily access it.
3. Add the following code to your head class:
`<link rel="stylesheet" type="text/css" href="(File Path)/override.css?v=2">`

*(The "?v=2" is a neat trick to clear css cache when you update the file, you can remove it for production if you are satisfied.)*
