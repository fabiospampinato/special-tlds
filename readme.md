# Special TLDs

List of special-use ICANN TLDs.

## Install

```sh
npm install special-tlds
```

## Usage

This list could be used for adding support for special-use TLDs to [linkify-it](https://github.com/markdown-it/linkify-it).

```ts
import linkify from 'linkify-it';
import tlds from 'special-tlds';

// Let's add these TLDs to linkify-it

const instance = linkify ();

instance.tlds ( tlds, true ); // It's important to pass "true", as that ensures the default TLDs will be still supported, as this package doesn't provide them
```

## License

MIT © Fabio Spampinato
