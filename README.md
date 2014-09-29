#  Ember Simple Auth Cookie Store

This is an npm package that contains the Ember Simple Auth Cookie Store
extension library packaged as an
[Ember CLI](https://github.com/stefanpenner/ember-cli) Addon.

## Installation

**Ember Simple Auth Cookie Store requires at least Ember CLI 0.0.44.**

To install simply run

```
npm install --save-dev ember-cli-simple-auth-cookie-store
ember generate ember-cli-simple-auth-cookie-store
```

in your Ember CLI project's root.

### Configuration

Ember Simple Auth Cookie Store uses the Ember CLI project's configuration as
defined in `config/environment.js`. Configure values for
`ENV['simple-auth-cookie-store']`, e.g.:

```js
ENV['simple-auth-cookie-store'] = {
  cookieName: 'custom-cookie-name'
};
```

For the actual Ember Simple Auth repository see
https://github.com/simplabs/ember-simple-auth
