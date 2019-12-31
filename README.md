# Template project with vuetify and typescript

A bare empty project which bride the folowing vue stack

* vue 2, vue-router, vuex
* vuetify
* jest
* typescript

A first glance it appeared trivial to make a new project with this stack. Unfortunately it didn't work out-of-the-box when we followed the guides.
Small configuration tweaks are still needed here and there in order to get a comfortable working environment.

This is why I made this project template as a base to accelerate my future projects. The frontend world is moving really fast. At the time you saw this repository it might become obsolete, so please take in consideration before using it.

## Project setup

```bash
pnpm install
```

### Compiles and hot-reloads for development

```bash
pnpm run serve
```

### Compiles and minifies for production

```bash
pnpm run build
```

## Run your unit tests

If you want to experiment a library or a function then you should create a new unit test, play with it, `--watch` how it will going when you change the codes.. Here how you can do it.

### Run all unit tests

```bash
pnpm run test:unit
```

or

```bash
npx jest
```

### Run one individual unit test

```bash
npx jest tests/unit/example.spec.spec.ts
```

### Watch unit test(s)

just add the `--watch` option, for eg:

```bash
npx jest tests/unit/example.spec.spec.ts --watch
```

## Lints and fixes files

```bash
pnpm run lint
```

### Other method to re-Format all the codes

Install `prettier`

```bash
pnpm i -g prettier
```

Reformat all the codes in the `src` and `tests` folder

```bash
prettier --write src/* src/**/* tests/* tests/**/*
```

## Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
