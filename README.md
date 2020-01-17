# Special TLDs

List of special-use ICANN TLDs.

## Install

```sh
npm install --save special-tlds
```

## Usage

This list could be used for adding support for special-use TLDs to [linkify-it](https://github.com/markdown-it/linkify-it).

```ts
import linkify from 'linkify-it';
import tlds from 'special-tlds';

const instance = linkify ();

instance.tlds ( tlds, true );
```

## License

MIT © Fabio Spampinato
