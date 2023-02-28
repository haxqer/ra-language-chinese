# Chinese Messages for React-Admin

## Installation

### version 4

```sh
yarn add @haxqer/ra-language-chinese@latest

# or

npm install @haxqer/ra-language-chinese@latest
```

## Usage

```jsx
import polyglotI18nProvider from 'ra-i18n-polyglot';
import chineseMessages from '@haxqer/ra-language-chinese';

const i18nProvider = polyglotI18nProvider(() => chineseMessages, 'zh');

<Admin i18nProvider={i18nProvider}>
  ...
</Admin>
```

See React-admin [documentation](https://marmelab.com/react-admin/Translation.html) for more information.
