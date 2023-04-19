# Cowsays Fortune
## About
A port of the linux command cowsay $(fortune) using an embeded port of Piuccio's [cowsay](https://www.npmjs.com/package/cowsay) to html and a formated version of [fortune](https://wiki.archlinux.org/title/Fortune) condensed into a single javascript array.
## Useage
Inlude the following code in the body of your html page.
```
<pre id="cowsay-target"></pre>
<script src="https://cdn.rawgit.com/Michael-Tennant/cowsays-fortune/main/script.js"></script>
```

Note: uses a git mirror to allow the file to be imported as raw text.

Alternatively if you would like a turtle to say these things import the `turtle-script.js` as opposed to `script.js`
