# DocFX Material

A simple material theme for [DocFX](https://dotnet.github.io/docfx/). This is an
override of the default template so you need to enable both in the `docfx.json`.

The colors were chosen using <https://material.io/tools/color>.

![DocFX Material Site](./docs/images/index/docfx-screenshot.png)

## Install

1. Download the source or the zipped file from the [releases](https://github.com/ovasquez/docfx-material/releases).
2. Create a `templates` folder in the root of your DocFX directory.
3. Copy the `material` folder to the `templates` folder.
4. Update the `docfx.json` configuration to include the material template:
    ```json
    {
        "template": [
            "default",
            "templates/material"
        ],
    }
    ```

## Color customization

You can easily customize the color of the header bar and the links by updating
the following variables in the `material/styles/main.css` file.

```css
/* COLOR VARIABLES*/
:root {
  --header-bg-color: #0d47a1;
  --header-ft-color: #fff;
  --highlight-light: #5e92f3;
  --highlight-dark: #003c8f;
  --font-color: #34393e;
}
```
