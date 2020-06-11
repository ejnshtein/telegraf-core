# @telegraf/core

[![node](https://img.shields.io/node/v/@telegraf/core.svg?style=flat-square)](https://www.npmjs.com/package/@telegraf/core)
[![Telegraf Version](https://img.shields.io/badge/Telegraf-3.36.0-f36caf.svg?style=flat-square)](https://telegraf.js.org)

This is modern version of [Telegraf](https://telegraf.js.org) Bot Framework for [Telegram](https://telegram.org).  

*Currently in development progress*

Future features:
- ESM modules
- Async/Await
- Working Typings*
- Small size*

\* When it will actually be rewritten.
## Installation

Currently in order to use this package, you should install telegraf first. 

```
npm i telegraf@latest // Latest version is recommended.
```

And now we can install our wrapper

```
$ npm install @telegraf/core
```
or using `yarn`:
```
$ yarn add @telegraf/core
```

## Usage

```js
import Telegraf from '@telegraf/core'

const bot = new Telegraf('token')

bot.start(async ctx => {
  return ctx.reply(`Hello ${ctx.from.username} !`)
})

bot.start()
```

## But why?

This package aims to reduce end project size by splitting all secondary features into a bunch of smaller ones.  
_More coming soon..._
