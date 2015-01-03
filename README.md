# &lt;social-media-icons&gt;

> A Polymer element with a set of scalable social media icons

![alt tag](http://www.hejty.com/github/social-media-320.png)

## Demo

[Check it live!](http://hejty.github.io/hejty/social-media-icons/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install social-media-icons --save
```

Or [download as ZIP](https://github.com/hejty/social-media-icons/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.5.2/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="social-media-icons/social-media-icons.html">
    ```

3. Start using it!

    ```html
    <social-media-icons></social-media-icons>
    ```

## Options

Attribute       | Options                                                   | Default                       | Description
---             | ---                                                       | ---                           | ---
`icon`         	| `behance`, `dribbble`, `facebook`, `github`, `googleplus`, `instagram`, `lastfm`, `pinterest`, `soundcloud`, `tumblr`, `twitter`    | `github`                      | Logo
`size`          | *int*                                                     | `32`                         	| The size of icon
`color`         | *hex*                                                  	| -     						| The fill color
`href`          | *string*                                                  | -                           | The target URL

## Examples:

```html
<social-media-icons icon="github" color="#bada55" size="320" href="https://github.com/hejty"></social-media-icons>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request ;)

## History

For detailed changelog, check [Releases](https://github.com/hejty/social-media-icons/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
