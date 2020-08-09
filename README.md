# use-constructor

[![GitHub stars](https://img.shields.io/github/stars/codejamninja/use-constructor.svg?style=social&label=Stars)](https://github.com/codejamninja/use-constructor)

> react hook that behaves like a class constructor for functional components

Please ★ this repo if you found it useful ★ ★ ★

## Installation

```sh
npm install --save use-constructor
```

## Usage

```ts
import React, { FC } from 'react';
import useConstructor from 'use-constructor';

const Component: FC = () => {
  useConstructor(() => {
    console.log('component will mount');
  });

  return <></>;
}
```

## Support

Submit an [issue](https://github.com/codejamninja/use-constructor/issues/new)

## Screenshots

[Contribute](https://github.com/codejamninja/use-constructor/blob/master/CONTRIBUTING.md) a screenshot

## Contributing

Review the [guidelines for contributing](https://github.com/codejamninja/use-constructor/blob/master/CONTRIBUTING.md)

## License

[MIT License](https://github.com/codejamninja/use-constructor/blob/master/LICENSE)

[Jam Risser](https://codejam.ninja) © 2020

## Changelog

Review the [changelog](https://github.com/codejamninja/use-constructor/blob/master/CHANGELOG.md)

## Credits

- [Jam Risser](https://codejam.ninja) - Author

## Support on Liberapay

A ridiculous amount of coffee ☕ ☕ ☕ was consumed in the process of building this project.

[Add some fuel](https://liberapay.com/codejamninja/donate) if you'd like to keep me going!

[![Liberapay receiving](https://img.shields.io/liberapay/receives/codejamninja.svg?style=flat-square)](https://liberapay.com/codejamninja/donate)
[![Liberapay patrons](https://img.shields.io/liberapay/patrons/codejamninja.svg?style=flat-square)](https://liberapay.com/codejamninja/donate)
