# &lt;social-media-icons&gt;

> A Polymer element with a set of scalable social media icons

![alt tag](http://hejty.github.io/demos/social-media-icons/preview.png)

## Demo

[Check it live!](http://hejty.github.io/demos/social-media-icons/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install social-media-icons --save
```

Or [download as ZIP](https://github.com/hejty/social-media-icons/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.7.7/webcomponents-lite.min.js"></script>
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

Attribute       | Options                                         | Default                       | Description
---             | ---                                             | ---                           | ---
`icon`         	| `dribbble`, `facebook`, `github`, `googleplus`, `instagram`, `lastfm`, `linkedin`, `medium`, `quora`, `pinterest`, `skype`, `spotify`, `stumbleupon`, `tumblr`, `twitter`, `youtube`, `vimeo`, `vine`    | `github`                      | The `icon` attribute grabs a vector-shaped logo of social media you choose
`size`          | *int*                                           | `32`                         	| The `size` attribute sets a size of an element
`color`         | *hex*                                           | -     						            | The `color` attribute fills the shape with a color you choose
`href`          | *string*                                        | -                             | The `href` attribute sets the target URL
`newTab`        | *boolean*                                       | false                         | The `newTab` attribute opens the linked icon on new browser tab

## Example

```html
<social-media-icons icon="github" color="#bada55" size="320" href="https://github.com/hejty" new-tab></social-media-icons>
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
