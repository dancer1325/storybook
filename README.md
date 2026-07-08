<p align="center">
  <a href="https://storybook.js.org/?ref=readme">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/263385/199832481-bbbf5961-6a26-481d-8224-51258cce9b33.png">
      <img src="https://user-images.githubusercontent.com/321738/63501763-88dbf600-c4cc-11e9-96cd-94adadc2fd72.png" alt="Storybook" width="400" />
    </picture>
  </a>
</p>

* Storybook 
  * == frontend workshop /
    * open source
    * free
  * allows
    * building isolated UI components & pages 
      * isolated == WITHOUT run WHOLE app
  * uses
    * UI 
      * development
      * testing
      * documentation
  * [use cases](https://storybook.js.org/showcase?ref=readme)

## Getting Started

### Documentation

* [here](docs/index.md)
* _Examples:_
  * [|Stackblitz](https://storybook.new)

Storybook comes with a lot of [addons](https://storybook.js.org/docs/configure/user-interface/storybook-addons?ref=readme) for component design, documentation, testing, interactivity, and so on
* Storybook's API makes it possible to configure and extend in various ways
* It has even been extended to support React Native, Android, iOS, and Flutter development for mobile.

## Projects

### Supported Frameworks

| Renderer                                                       | Demo                                                                                                                                                                         |                                                                                                                                                       |
| -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [React](code/renderers/react)                                  | [![Storybook demo](https://img.shields.io/npm/v/@storybook/react/latest?style=flat-square&color=blue&label)](https://next--630511d655df72125520f051.chromatic.com/)          | [![React](https://img.shields.io/npm/dm/@storybook/react?style=flat-square&color=eee)](code/renderers/react)                                          |
| [Angular](code/frameworks/angular/)                            | [![Storybook demo](https://img.shields.io/npm/v/@storybook/angular/latest?style=flat-square&color=blue&label)](https://next--6322ce6af69825592bbb28fc.chromatic.com/)        | [![Angular](https://img.shields.io/npm/dm/@storybook/angular?style=flat-square&color=eee)](code/frameworks/angular/)                                  |
| [Vue 3](code/renderers/vue3)                                   | [![Storybook demo](https://img.shields.io/npm/v/@storybook/vue3/latest?style=flat-square&color=blue&label)](https://next--630513346a8e284ae244d415.chromatic.com/)           | [![Vue 3](https://img.shields.io/npm/dm/@storybook/vue3?style=flat-square&color=eee)](code/renderers/vue3/)                                           |
| [Web components](code/renderers/web-components)                | [![Storybook demo](https://img.shields.io/npm/v/@storybook/web-components/latest?style=flat-square&color=blue&label)](https://next--638db5bf49adfdfe8cf545e0.chromatic.com/) | [![Svelte](https://img.shields.io/npm/dm/@storybook/web-components?style=flat-square&color=eee)](code/renderers/web-components)                       |
| [React Native](https://github.com/storybookjs/react-native)    | [![](https://img.shields.io/npm/v/@storybook/react-native/latest?style=flat-square&color=blue&label)](/)                                                                     | [![React Native](https://img.shields.io/npm/dm/@storybook/react-native?style=flat-square&color=eee)](https://github.com/storybookjs/react-native)     |
| [HTML](code/renderers/html)                                    | [![Storybook demo](https://img.shields.io/npm/v/@storybook/html/latest?style=flat-square&color=blue&label)](https://next--63dd39a158cf6fc05199b4bb.chromatic.com/)           | [![HTML](https://img.shields.io/npm/dm/@storybook/html?style=flat-square&color=eee)](code/renderers/html)                                             |
| [Ember](code/frameworks/ember/)                                | [![](https://img.shields.io/npm/v/@storybook/ember/latest?style=flat-square&color=blue&label)](/)                                                                            | [![Ember](https://img.shields.io/npm/dm/@storybook/ember?style=flat-square&color=eee)](code/frameworks/ember/)                                        |
| [Svelte](code/renderers/svelte)                                | [![Storybook demo](https://img.shields.io/npm/v/@storybook/svelte/latest?style=flat-square&color=blue&label)](https://next--630873996e4e3557791c069c.chromatic.com/)         | [![Svelte](https://img.shields.io/npm/dm/@storybook/svelte?style=flat-square&color=eee)](code/renderers/svelte)                                       |
| [Preact](code/renderers/preact)                                | [![Storybook demo](https://img.shields.io/npm/v/@storybook/preact/latest?style=flat-square&color=blue&label)](https://next--63b588a512565bfaace15e7c.chromatic.com/)         | [![Preact](https://img.shields.io/npm/dm/@storybook/preact?style=flat-square&color=eee)](code/renderers/preact)                                       |
| [Qwik](https://github.com/literalpie/storybook-framework-qwik) | [![](https://img.shields.io/npm/v/storybook-framework-qwik/latest?style=flat-square&color=blue&label)](/)                                                                    | [![Qwik](https://img.shields.io/npm/dm/storybook-framework-qwik?style=flat-square&color=eee)](https://github.com/literalpie/storybook-framework-qwik) |
| [SolidJS](https://github.com/solidjs-community/storybook)      | [![](https://img.shields.io/npm/v/storybook-solidjs-vite/latest?style=flat-square&color=blue&label)](/)                                                                      | [![SolidJS](https://img.shields.io/npm/dm/storybook-solidjs-vite?style=flat-square&color=eee)](https://github.com/solidjs-community/storybook)        |
| [Android, iOS, Flutter](https://github.com/storybookjs/native) | [![](https://img.shields.io/npm/v/@storybook/native/latest?style=flat-square&color=blue&label)](/)                                                                           | [![Native](https://img.shields.io/npm/dm/@storybook/native?style=flat-square&color=eee)](https://github.com/storybookjs/native)                       |

### Addons

| Addons                                                                    |                                                                            |
| ------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [a11y](code/addons/a11y/)                                                 | Test components for user accessibility in Storybook                        |
| [actions](code/core/src/actions/)                                         | Log actions as users interact with components in the Storybook UI          |
| [backgrounds](code/core/src/backgrounds)                                  | Let users choose backgrounds in the Storybook UI                           |
| [cssresources](https://github.com/storybookjs/addon-cssresources)         | Dynamically add/remove CSS resources to the component iframe               |
| [design assets](https://github.com/storybookjs/addon-design-assets)       | View images, videos, and weblinks alongside your story                     |
| [docs](code/addons/docs/)                                                 | Add high quality documentation to your components                          |
| [events](https://github.com/storybookjs/addon-events)                     | Interactively fire events to components that respond to EventEmitter       |
| [google-analytics](https://github.com/storybookjs/addon-google-analytics) | Reports google analytics on stories                                        |
| [graphql](https://github.com/storybookjs/addon-graphql)                   | Query a GraphQL server within Storybook stories                            |
| [jest](https://github.com/storybookjs/addon-jest)                         | View the results of components' unit tests in Storybook                    |
| [links](code/addons/links/)                                               | Create links between stories                                               |
| [measure](code/core/src/measure/)                                         | Visually inspect the layout and box model within the Storybook UI          |
| [outline](code/core/src/outline/)                                         | Visually debug the CSS layout and alignment within the Storybook UI        |
| [query params](https://github.com/storybookjs/addon-queryparams)          | Mock query params                                                          |
| [viewport](code/core/src/viewport/)                                       | Change display sizes and layouts for responsive components using Storybook |

See [Addon / Framework Support Table](https://storybook.js.org/docs/configure/integration/frameworks-feature-support?ref=readme)

To continue improving your experience, we have to eventually deprecate or remove certain addons in favor of new and better tools.

If you're using info/notes, we highly recommend you migrate to [docs](code/addons/docs/) instead, and [here is a guide](code/addons/docs/docs/recipes.md#migrating-from-notesinfo-addons) to help you.

If you're using contexts, we highly recommend you migrate to [toolbars](https://github.com/storybookjs/storybook/tree/next/code/addons/toolbars) and [here is a guide](https://github.com/storybookjs/storybook/blob/next/MIGRATION.md#deprecated-addon-contexts) to help you.

If you're using addon-storyshots, we highly recommend you migrate to the Storybook [test-runner](https://github.com/storybookjs/test-runner) and [here is a guide](https://storybook.js.org/docs/writing-tests/storyshots-migration-guide?ref=readme) to help you.

## Badges & Presentation materials

We have a badge! Link it to your live Storybook example.

![Storybook](https://cdn.jsdelivr.net/gh/storybookjs/brand@main/badge/badge-storybook.svg)

```md
[![Storybook](https://cdn.jsdelivr.net/gh/storybookjs/brand@main/badge/badge-storybook.svg)](link to site)
```

If you're looking for material to use in your Storybook presentation, such as logos, video material, and the colors we use, you can find it all on our [brand repo](https://github.com/storybookjs/brand).

## Community

- Tweeting via [@storybookjs](https://x.com/storybookjs)
- Blogging at [storybook.js.org](https://storybook.js.org/blog/?ref=readme) and [Medium](https://medium.com/storybookjs)
- Chatting on [Discord](https://discord.gg/storybook)
- Videos and streams at [YouTube](https://www.youtube.com/channel/UCr7Quur3eIyA_oe8FNYexfg)

## Contributing

Contributions to Storybook are always welcome!

- 📥 Pull requests and 🌟 Stars are always welcome.
- Read our [contributing guide](CONTRIBUTING.md) to get started,
  or find us on [Discord](https://discord.gg/storybook), we will take the time to guide you.

Looking for a first issue to tackle?

- We tag issues with [![Good First Issue](https://img.shields.io/github/issues/storybookjs/storybook/good%20first%20issue.svg)](https://github.com/storybookjs/storybook/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) when we think they are well suited for people who are new to the codebase or OSS in general.
- [Talk to us](https://discord.gg/storybook), we'll find something that suits your skills and learning interests.

### Development scripts

Storybook is organized as a monorepo
* Useful scripts include:

#### `yarn start`

> Runs a sandbox template storybook with test stories

#### `yarn task`

> As above, but gives you options to customize the sandbox (e.g. selecting other frameworks)

#### `yarn lint`

> boolean check if code conforms to linting rules - uses remark & eslint

- `yarn lint:js` - will check js
- `yarn lint:md` - will check markdown + code samples
- `yarn lint:js --fix` - will automatically fix js

#### `yarn test`

> boolean check if unit tests all pass - uses jest

- `yarn run test --core --watch` - will run core tests in watch-mode
