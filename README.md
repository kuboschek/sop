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
var songInfo = [{
        id: "miles-away",
        fileLocation: "fl/masters/280320.wav",
        fileType: "audio/wav",

        coverLocation: "covers/miles-away.jpg",

        title: "Miles Away",
        album: "f**k i think i made another rap track",
        artist:"kubs"
    },
    {
        id: "suicide-by-train",
        fileLocation: "fl/masters/290320.flac",
        fileType: "audio/flac",

        coverLocation: "covers/suicide-by-train.jpg",

        title: "Suicide By Train",
        album: "f**k i think i made another rap track",
        artist:"kubs"
    }
];
```

## Deploy

* Adjust song info as described above
* Copy updated `index.html` and `style.css` to your web server
* Copy audio file and cover picture to your web server


## Assumptions

* The cover picture is square

