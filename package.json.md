# package.json

```json
{
  "name": "complete-intro-to-react-v5",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "format": "prettier \"src/**/*.{js,html}\" --write",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/btholt/complete-intro-to-react-v5.git"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/btholt/complete-intro-to-react-v5/issues"
  },
  "homepage": "https://github.com/btholt/complete-intro-to-react-v5#readme",
  "devDependencies": {
    "prettier": "^1.19.1"
  }
}
```

## Notes
The `format` command in scripts specifies that prettier should run on all `js` and `html` files within the any folder within the `src` directory. The `--write` flag indicates that prettier should modify any documents that need formatting and save them.
