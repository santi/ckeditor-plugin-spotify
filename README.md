# CKEditor Spotify Plugin

Plugin for adding a [Spotify Embed](https://developer.spotify.com/documentation/widgets/guides/adding-a-spotify-embed/) to the CKEditor.

Supports both Spotify URIs (spotify:album:1DFixLWuPkv3KT3TnV35m3) and Spotify URLs ([http://open.spotify.com/track/6rqhFgbbKwnb9MLmUQDhG6](http://open.spotify.com/track/6rqhFgbbKwnb9MLmUQDhG6)).

Requires `CKEditor 4.3+` with the `widget` plugin . The editor instance must allow `div` and `iframe` tags.

The plugin uses a few custom styles. These are automatically included in the [classic editor](https://ckeditor.com/docs/ckeditor4/latest/examples/classic.html) instance, but must be copied for [inline editors](https://ckeditor.com/docs/ckeditor4/latest/examples/inline.html) and for the final target webpage. To include the custom styles into your editor/webpage, include the following in the `<head>` of your document:

```html
<head>
  <link
    rel="stylesheet"
    href="<PATH_TO_CKEDITOR>/plugins/spotify/styles/spotify.css"
  />
</head>
```

Published in the official [CKEditor plugin repository](https://ckeditor.com/cke4/addon/spotify).

## Translations

Currently supports English (en), Norwegian Bokmål (nb) and Ukrainian (uk). Want to provide translations for your own language? Please fork the project and open a pull request.

## Screenshots

<img src="/screenshots/spotify-plugin-dialog.png?raw=true" alt="Dialog screenshot" width="300">
<img src="/screenshots/spotify-plugin-small-widget.png?raw=true" alt="Small widget screenshot" width="300">
<img src="/screenshots/spotify-plugin-large-widget.png?raw=true" alt="Large widget screenshot" width="300">
<img src="/screenshots/spotify-plugin-multiple-widgets.png?raw=true" alt="Multiple widgets screenshot" width="300">

## Credits

<div>Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/"             title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/"             title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>

# Development

Run `npx live-server .` in root folder and open `http://localhost:8080/demo` to test out the plugin in an editor instance.
