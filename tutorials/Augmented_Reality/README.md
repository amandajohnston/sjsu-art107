# **AUGMENTED REALITY**

### **++[SJSU Art 107 Fall 2019 Home Page](https://carriehott.github.io/sjsu-art107/)++**
[<Back to Tutorials](https://carriehott.github.io/sjsu-art107/tutorials)

# Augmented Reality

## Resources
Visit [Jerome Etienne’s main AR.js github site](https://jeromeetienne.github.io/AR.js/) for full list of resources and links.

## Augmented Reality on Medium:
These are short guides to help you with AR. Note that some were written a year or two ago, and the libraries have updated since then. Keep track of the library versions - and update your scripts when things get buggy.  

* [Augmented Reality in 10 lines of HTML](https://medium.com/arjs/augmented-reality-in-10-lines-of-html-4e193ea9fdbf)

* [Tips & Tricks to Spice Up Your AR](https://medium.com/@aschmelyun/tips-tricks-to-spice-up-your-ar-js-projects-fa89bc2ec296)

* [Using 3-D Models with AR.js and a-frame](https://medium.com/@akashkuttappa/using-3d-models-with-ar-js-and-a-frame-84d462efe498)

* [AR.js The Simplest Way to Get Cross Browser AR on the web](https://medium.com/swlh/ar-js-the-simplest-way-to-get-cross-browser-augmented-reality-on-the-web-10cbc721debc)

* [A computer’s understanding of space for Augmented Reality](https://medium.com/hackernoon/a-computers-understanding-of-space-for-augmented-reality-c0fd40a52900)


## A-frame & AR.js:
* [The AR tutorial on a-frame](https://medium.com/swlh/ar-js-the-simplest-way-to-get-cross-browser-augmented-reality-on-the-web-10cbc721debc)

* [A-frame School](https://aframe.io/aframe-school/)

* [A-frame Documentation](https://aframe.io/docs/0.9.0/introduction/)

* [A-frame FAQ](https://aframe.io/docs/0.9.0/introduction/faq.html)

### AR In-Class Demo

[![AR](AR_1.png)](https://docs.google.com/presentation/d/1TuGT5AjpLSi-sgJvrnH_5foEBYE_HG37R9qr2HEbCzI/edit?usp=sharing)

#### **Code to copy to index.html in your AR repository:**

    <!doctype HTML>
    <html>
    <!-- This is a link to the latest A-Frame library-->
    <script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>

    <!-- This is a link to the ar.js library for A-Frame -->
    <script src="https://jeromeetienne.github.io/AR.js/aframe/build/aframe-ar.js"></script>

    <body style='margin : 0px; overflow: hidden;'>

    <a-scene embedded arjs>

    <a-marker-camera preset="hiro">

    <a-cylinder position= "0 0.5 0" material= "color: yellow" height=".5" radius=".25"></a-cylinder>

    <a-text value="Hello Art 107!!" position="-0.5 0 -1" color="#FF16EB" rotation="-45 0 0"></a-text>

    </a-marker>

    <a-entity camera></a-entity>

    </a-scene>

    </body>

    </html>
