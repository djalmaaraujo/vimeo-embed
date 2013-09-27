# &lt;vimeo-embed&gt;

Web Component wrapper for Vimeo's player using Polymer.

> Maintained by [Djalma Araújo](https://github.com/djalmaaraujo).

## Demo

> [Check it live](http://djalmaaraujo.github.io/vimeo-embed/).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="lib/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/vimeo.html">
	```

3. Start using it!

	```html
	<vimeo-embed videoid="871892738923"></vimeo-embed>
	```

## Options

Attribute     | Options         | Default                                    | Description
---           | ---             | ---                                        | ---
`videoid`     | *int*           | ``                                         | **Required** ID specifies the vimeo URL
`width`       | `int`,          |                                            | iframe width
`height`      | `int`,          |                                            | iframe height
`frameborder` | `int`,          |  0                                         | iframe border


> See vimeo' [official documentation](http://developer.vimeo.com/player/embedding#universal-parameters) for more parameters.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
