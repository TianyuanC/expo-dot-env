# expo-dot-env

Minimal example to access inline environment variables

## Start

```bash
# After restarting your simulator
yarn install && yarn start
```

## Steps

1. `package.json`

```bash
"start": "REACT_NATIVE_HOST=127.0.0.1 expo start"
```

Environment variable need to have `REACT_NATIVE_` prefix

2. `App.js`

```html
<Text>
    There is no place like {process.env.REACT_NATIVE_HOST}
</Text>
```

## Screenshot

<img src="./screenshot.png" width="400">
