# Vite root resolution bug

The `--root` flag seems to do nothing.

## Steps to reproduce

1. Clone this repo
2. Run `npm install`
3. Run `npm start` and open the page
4. Page is blank

## Expected behaviour

Page should display the contents of `/foo/index.html`