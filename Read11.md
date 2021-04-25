# Audio, Video, Images

## Audio

*To play an audio file in HTML, use the `<audio>` element*

### HTML Audio - How It Works

*The controls attribute adds audio controls, like play, pause, and volume.*

The `<source>` element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.

>The text between the `<audio>` and `</audio>` tags will only be displayed in browsers that do not support the `<audio>` element.

### HTML `<audio>` Autoplay

To start an audio file automatically, use the autoplay attribute

Like : `<audio controls autoplay>`

## Video

The HTML `<video>` element is used to show a video on a web page.

To show a video in HTML, use the `<video>` element.

### How it Works

* The controls attribute adds video controls, like play, pause, and volume.

* It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

* The `<source>` element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

* The text between the `<video>` and `</video>` tags will only be displayed in browsers that do not support the `<video>` element.

### HTML `<video>` Autoplay

**To start a video automatically, use the autoplay attribute**

Add muted after autoplay to let your video start playing automatically (but muted): `<video width="320" height="240" autoplay muted>`

## Image

*Images can improve the design and the appearance of a web page.*

Image Tags: `<img src="" alt="">`

src : **Return the source of image starting by `./` .**

alt : **Specifies an alternate text for the image**

### The src Attribute

**The required src attribute specifies the path (URL) to the image.**

**Note**: *When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.*

