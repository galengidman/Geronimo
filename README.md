# Geronimo 💥

Geronimo is a jQuery/Zepto plugin that makes parallax backgrounds super-simple. No annoying configuration, frustrating math, or general misery. Just install, call, and you're good-to-go!

## Installing

First, include either jQuery or Zepto on the page, followed by Geronimo.

```html
<script src="path/to/jquery.min.js"></script>
<script src="path/to/geronimo.min.js"></script>
```

Then call `.geronimo()` on the background elements you'd like to parallaxify.

```html
<section class="section">
  <div class="section-background" style="background-image: url('some/background/image.jpg')"></div>
  <!-- the rest of your section content here -->
</section>

<script>
  $( document ).ready( function() {
    $( '.section-background' ).geronimo();
  } );
</script>
```

## Browser support

IE10+, all recent versions of everything else.

## How to build

Assuming you have Node.js and NPM installed...

```
$ npm install
$ gulp
```

If not, [here's how you do that](https://docs.npmjs.com/getting-started/installing-node).

## License

Geronimo is licensed under the [MIT License](https://opensource.org/licenses/MIT).
