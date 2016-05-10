#My clone of SVG Crowbar

Adds the ability to save SVG content as a PNG file, and allows you to specifiy the filename. Tested on Chrome and used on WebPageTest.org. Beyond that - your mileage may vary :-)

You can add this as a bookmarklet by creating a bookmark and adding the following as the link (I can't create a bookmarklet in markdown)

```javascript
javascript: (function () { var e = document.createElement('script'); e.setAttribute('src', 'https://rawgit.com/marklkelly/svg-crowbar/gh-pages/svg-crowbar.js'); e.setAttribute('class', 'mk-svg-crowbar'); document.body.appendChild(e); })();
```

A Chrome-specific bookmarklet that extracts SVG nodes and accompanying styles from an HTML document and downloads them as an SVG file—A file which you could open and edit in Adobe Illustrator, for instance. Because SVGs are resolution independent, it’s great for when you want to use web technologies to create documents that are meant to be printed (like, maybe on newsprint). It was created with [d3.js](http://d3js.org) in mind, but it should work fine with any SVG.

[Project page](http://nytimes.github.com/svg-crowbar/)
