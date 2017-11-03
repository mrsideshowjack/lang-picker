[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mrsideshowjack/lang-picker)


# \<lang-picker\>

`lang-picker` Language picker dropdown element, built with paper-dropdown-menu returns short language code eg: 'en'

![](https://cl.ly/2W0o2L431z06/Screen%20recording%202017-11-03%20at%2011.45.36%20AM.gif)

## Installation

```
$ bower install --save mrsideshowjack/lang-picker
```

## Usage

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="lang-picker.html">
  </template>
</custom-element-demo>
```
-->
```html
<lang-picker selected="{{lang}}"></lang-picker>
```


### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--lang-picker-dropdown-width` | width of the dropdown | `100%`
`--lang-picker-listbox-max-height` | max-height of the listbox | `250px`
`--paper-input-container-focus-color` | colour of the input container | `--primary-color, blue`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

(c) Jack Mason Apache License 2.0