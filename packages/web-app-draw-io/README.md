# web-app-draw-io

This application can be used for creating, opening and editing `.drawio` files.

## Configuration

In `apps.yaml` you can override configuration like this:

```yaml
draw-io:
  config:
    showMenuItem: true
    url: 'https://embed.diagrams.net'
    theme: 'minimal'
```

### Options

- **`showMenuItem`** _(boolean, optional)_ - Controls whether the Draw.io menu item should appear in the application menu, if the user has a personal space. Defaults to `true`. Set to `false` to hide the menu item while keeping the rest of the extension functional.
- **`url`** _(string, optional)_ - The URL of the Draw.io embed server.
- **`theme`** _(string, optional)_ - The Draw.io theme to use.
