# Intercom Facade

Solves the '[Lazy load third-party resources with facades](https://web.dev/third-party-facades/)' warning for Intercom's chat widget. A pure JavaScript adaptation of Calibre's [React Live Chat Loader](https://github.com/calibreapp/react-live-chat-loader).

## Installation

To download intercom-facade, run:

```bash
npm install --save intercom-facade
```

Alternatively, use the built/minified version of the latest tagged release in `dist/`.

## Usage

Simply use intercom-facade in place of Intercom's embed snippet:

```html
<script>
window.intercomSettings = {
  app_id: 'abc123',
  background_color: '#22CFC6', // optional, defaults to #333333.
}
</script>
<script src="/path/to/intercom-facade.min.js"></script>
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
