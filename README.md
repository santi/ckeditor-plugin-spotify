# CKEditor Spotify Plugin

Plugin for adding a [Spotify Play Button](https://developer.spotify.com/documentation/widgets/guides/adding-a-spotify-play-button/) to the CKEditor.

Requires `CKEditor 4.3+` with plugin `widget`. The editor instance must allow `div` and `iframe` tags.

The plugin uses a few custom styles. There are automatically included in the [classic editor](https://ckeditor.com/docs/ckeditor4/latest/examples/classic.html) instance, but must be copied for [inline editors](https://ckeditor.com/docs/ckeditor4/latest/examples/inline.html) and for the final target webpage. To include the custom styles into your editor/webpage, include the following the `<head>` of your document:

```html
<head>
    <link rel="stylesheet" href="<PATH_TO_CKEDITOR>/plugins/spotify/styles/spotify.css">
</head>
```


# Translations

Currently supports English (en) and Norwegian Bokmål (nb). Do you want to provide translations for your own language? Please fork the project and open a pull request.


# Credits

<div>Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/"             title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/"             title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>