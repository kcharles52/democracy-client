![Screenshot](https://github.com/demokratie-live/democracy-assets/blob/master/images/forfb2.png)

# Democracy-Client &nbsp; <a href="https://github.com/kriasoft/nodejs-api-starter/stargazers" target="_blank"><img src="https://img.shields.io/github/stars/demokratie-live/democracy-client.svg?style=social&label=Star&maxAge=3600" height="20"/></a> <a href="https://twitter.com/democracy_de" target="_blank"><img src="https://img.shields.io/twitter/follow/democracy_de.svg?style=social&label=Follow&maxAge=3600" height="20"/></a> <a href="https://www.facebook.com/democracygermany/" target="_blank"><img src="https://github.com/demokratie-live/democracy-assets/blob/master/docu/facebook.png" height="20"/></a> <a href="https://discord.gg/Pdu3ZEV" target="_blank"><img src="https://github.com/demokratie-live/democracy-assets/blob/master/docu/discord.png" height="20"/></a>

[![Build Status](https://travis-ci.org/demokratie-live/democracy-client.svg?branch=master)](https://travis-ci.org/demokratie-live/democracy-client)

The Client for the DEMOCRACY App. This includes iOS and Android generated from the same Codebase.

:movie_camera: <a href="https://www.youtube.com/watch?v=H6oJA4MUVW0">Video des Entwicklungsstandes 26.02.2018</a><br>
:movie_camera: <a href="https://www.youtube.com/watch?v=oTX59JhDmXU">Video des Entwicklungsstandes 15.12.2017</a><br>
<br>
<a href="https://www.youtube.com/watch?v=H6oJA4MUVW0"><img src="https://github.com/demokratie-live/democracy-assets/blob/master/screenshots/Developer%20Demo%20Video%20-%20480p-spring4-optimized.gif" width="100%"></a>

[Entwicklertagebuch](https://github.com/demokratie-live/democracy-client/wiki/Entwicklertagebuch)

## Systemmap
![Systemmap](https://github.com/demokratie-live/democracy-docu/blob/master/app/Systemmap.png)

## Tech Stack

* [Node.js][node], [Yarn][yarn], [JavaScript][js], [Babel][babel], [Jest][jest]
* [ReactNative][reactnative], [Wix ReactNativeNavigation][wix], [StyledComponents][styledcomponents]

[More Dependecies](https://github.com/demokratie-live/democracy-client/network/dependencies)

![Projekt Struktur](https://github.com/demokratie-live/democracy-assets/blob/master/docu/api_structure_client.png)

## Prerequisites

* [Node.js][node]
* [Android Studio or Android SDK][android] follow the installation Instructions [here](http://facebook.github.io/react-native/docs/getting-started.html)
* [optional][windows] install windows-build-tools for node
  ```
  npm install --global --production windows-build-tools
  (installs python) (requireds administrator rights)
  ```

## Getting started

Clone the git repo & install packages
```
git clone git@github.com:demokratie-live/democracy-client.git
cd democracy-client
yarn install
```

### Create the config file and modify it accordingly
```
cp ./.env.debug.example ./.env.debug
touch ./.env.debug
```


### Compile and start Version of your choosing
```
yarn start:android
yarn start:ios
```

### Build only
```
yarn build:android
yarn build:ios
```

### Test Project
```
yarn test:lint
```

## Deployment

Deployment is done with Travis CI

## Contributing

Anyone and everyone is welcome to [contribute](CONTRIBUTING.md). Start by checking out the list of
[open issues](https://github.com/demokratie-live/democracy-client/issues).

## License

Copyright © 2017-present DEMOCRACY Deutschland e.V.. This source code is licensed under the Apache 2.0 license found in the
[LICENSE](https://github.com/demokratie-live/democracy-client/blob/master/LICENSE) file.

## Maintainers

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/ManAnRuck">
          <img width="150" height="150" src="https://github.com/ManAnRuck.png?v=3&s=150">
          </br>
          <strong>Manuel Ruck</strong>
        </a>
        <br>
        Maintainer
      </td>
      <td align="center">
        <a href="https://github.com/ulfgebhardt">
          <img width="150" height="150" src="https://github.com/ulfgebhardt.png?v=3&s=150">
          </br>
          <strong>Ulf Gebhardt</strong>
        </a>
        <br>
        Maintainer
      </td>
    </tr>
  <tbody>
</table>

---

Made with ♥ by Team DEMOCRACY ([democracy-deutschland.de](https://www.democracy-deutschland.de)), [startnext contributors](https://www.startnext.com/democracy/unterstuetzer/) and [contributors](https://github.com/demokratie-live/democracy-client/graphs/contributors)

[node]: https://nodejs.org
[yarn]: https://yarnpkg.com
[js]: https://developer.mozilla.org/docs/Web/JavaScript
[babel]: http://babeljs.io/
[reactnative]: http://www.reactnative.com/
[android]: https://developer.android.com/studio/index.html
[jest]: http://facebook.github.io/jest/
[wix]: https://github.com/wix/react-native-navigation
[styledcomponents]: https://github.com/styled-components/styled-components
