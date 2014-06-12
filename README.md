seajs-circular
=========

A Sea.js plugin for circular dependency

Install
-------

Install with spm:

    $ spm install seajs/seajs-circular


Usage
-----

```html
<script src="path/to/sea.js"></script>
<script src="path/to/seajs-circular.js"></script>

<script>

// seajs can load circular dependency module after loading circular plugin.
seajs.use("path/to/circular-mod")

</script>
```

Note
-----

This plugin bases on seajs ^2.3.0
<br/>When a circular dependency occurs, the program will function well as well as warning a message in console.

seajs 3.0.0 will native support circular dependency without this plugin.