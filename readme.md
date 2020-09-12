# Responsive header with bubbles
## Inspired by
* <a href="https://youtu.be/CZTCciHE72I">Easy Tutorials on YouTube</a>
* <a href="https://codepen.io/Mark_Bowley/pen/mEtqj">Mark Bowley on Codepen</a>

### SCSS
The code is written in VS Code and using Live Sass Compiler to compile and autoprefix the SCSS files.

To configure Live Sass Compiler to utilise the dist folder this is my JSON Settings
```
"liveSassCompile.settings.autoprefix": [
    "> 1%",
    "last 2 versions"
],
"liveSassCompile.settings.formats":[
    // This is Default.
    {
        "format": "expanded",
        "extensionName": ".css",
        "savePath": "/dist/css"
    },
    // You can add more
    {
        "format": "compressed",
        "extensionName": ".min.css",
        "savePath": "/dist/css"
    },
],
```

I also like to hide the output window using this
```
"liveSassCompile.settings.showOutputWindow": false
```

So here is the full JSON file

```
{
    "liveSassCompile.settings.autoprefix": [
        "> 1%",
        "last 2 versions"
    ],
    "liveSassCompile.settings.formats":[
        // This is Default.
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/dist/css"
        },
        // You can add more
        {
            "format": "compressed",
            "extensionName": ".min.css",
            "savePath": "/dist/css"
        },
    ],
    "liveSassCompile.settings.showOutputWindow": false
}
```