# Universally Unique Username

Easily generate random and unique usernames from a dictionary with thousands of words. Simple and lightweight.

## Install

```
npm i uuus
```

## Usage

```ts
import { generateUsername } from "uuus"

const username = generateUsername({
    maxLength: 16,
    capitalize: true,
    numberLength: 3
})

// JuicyFork330
// LightLlama539
// NosyPelican558
```

## Methods

### generateUsername

| Options      | Type        |           | Default value   |
|--------------|-------------|-----------|-----------------|
| maxLength    | `number`    | Maximum username length, including trailing number. | `32` |
| capitalize   | `boolean`   | Capitalize words | `false` |
| separator    | `string`    | Separator between words  | `""` |
| numberLength | `number`    | Length of random trailing number. Use `0` to disable. | `3` |
