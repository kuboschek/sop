# sop - song page

## Key Facts

* Just simple CSS + JS
* Works in any modern browser
* Hostable on GitHub Pages
* Adjustable to your liking

## Configure

To play your own song, change the data
at the top of ```index.html```:

```js
var songInfo = {
    fileLocation: "<location of your .wav file>",
    fileType: "audio/wav",

    coverLocation: "<location of SQUARE cover picture>",

    title: "<song title>",
    album: "<album title>",
    artist:"<artist name>"
}
```

## Deploy

* Adjust song info as described above
* Copy updated `index.html` and `style.css` to your web server
* Copy audio file and cover picture to your web server


## Assumptions

* The cover picture is square

