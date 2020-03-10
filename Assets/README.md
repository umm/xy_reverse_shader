# xy\_reverse\_shader

## What

XY Reverse Shaders is uGUI Shader to reverse x, y axis.

![reverse](./art/reverse_small.gif)

## Install

### With Unity Package Manager

```bash
upm add package dev.upm-packages.xy-reverse-shader
```

Note: `upm` command is provided by [this repository](https://github.com/upm-packages/upm-cli).

You can also edit `Packages/manifest.json` directly.

```jsonc
{
  "dependencies": {
    // (snip)
    "dev.upm-packages.xy-reverse-shader": "[latest version]",
    // (snip)
  },
  "scopedRegistries": [
    {
      "name": "Unofficial Unity Package Manager Registry",
      "url": "https://upm-packages.dev",
      "scopes": [
        "dev.upm-packages"
      ]
    }
  ]
}
```

### Any other else (classical umm style)

```shell
yarn add "umm/xy_reverse_shader#^1.0.0"
```

## Examples

See [Assets/Examples](./Assets/Examples) folder

## License

Copyright (c) 2019 Takuma Maruyama

Released under the MIT license, see [LICENSE.txt](LICENSE.txt)
