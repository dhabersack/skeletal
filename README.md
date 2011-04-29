# Skeletal

Skeletal is a blank slate for website creation. Instead of resetting default browser styling with a reset.css you then have to override, Skeletal comes with sensible defaults in its base.css.


## Features

### Units in text fields

You can add units to text fields by adding the custom attribute data-unit to the preceding label like this:

<label for="field" data-unit="mph">Miles per hour</label>
<input type="text" id="field" name="field" value="120">


## Known issues

Skeletal uses HTML5-tags (header, footer, nav, article, section and others) that are not supported by all browsers. Support for those will be added at a later point.

Currently built on Webkit, support for other browsers not included yet.


## Problems?

Please open [an issue][issues].


## Author

* Dominik Habersack / <dhabersack@gmail.com>


## License

Skeletal is relased under the [MIT License][license].


[issues]: http://github.com/dhabersack/skeletal/issues
[license]: http://github.com/dhabersack/skeletal/blob/master/LICENSE
