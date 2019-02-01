# DocFX Material

A simple material theme for DocFX. This is an override of the default template
so you need to enable both in the `docfx.json`.

The colors were chosen using <https://material.io/tools/color>.

![DocFX Material Site](./images/material-site.png)

## Install

1. Download the source or the zipped file from the release.
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

## Markdown extras

For more reference about markdown support in DocFX check the
[official documentation.](https://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html?tabs=tabid-1%2Ctabid-a#note-warningtipimportant) 

> [!NOTE]
> This is a note which needs your attention, but it's not super important.
>
> [!WARNING]
> This is a warning containing some important message.
>
> [!CAUTION]
> This is a warning containing some **very** important message.
