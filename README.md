# Jeedom-Widget-customTile

Provides a tile for a command inside the equipment tile.

![Dashboard 1](/img/dashboard1.png)
![Dashboard 2](/img/dashboard2.png)


## Multiple Personalization Options

You can customize the appearance of the tile using the following options:

- **transparency**: `0-1` (Transparency of the background color)
- **masterpreset**: Selection of the preset in additional CSS configuration
- **preset**: `heating | security | energy | light | opening | automatism | multimedia | default` (Category preset for the command, overrides custom color)
- **colortype**: `jeedom | analogues | complementaires | monochromatiques | foncees | pastel | vives | terre | type1 | type2 | type3 | type4 | type5` (Color type for the preset)
- **color**: `rgb(20,20,20)` (Custom background color)
- **separator**: `.|,` (Separator between integer and decimal parts)
- **titlefontcolor**: `rgb(20,20,20)` (Color of the title text)
- **valueintfontcolor**: `rgb(20,20,20)` (Color of the integer part of the value)
- **valuesepfontcolor**: `rgb(20,20,20)` (Color of the separator)
- **valuedecfontcolor**: `rgb(20,20,20)` (Color of the decimal part of the value)
- **unitfontcolor**: `rgb(20,20,20)` (Color of the unit text)
- **titlefontsize**: `NNpx` (Font size of the title text)
- **valueintfontsize**: `NNpx` (Font size of the integer part of the value)
- **valuesepfontsize**: `NNpx` (Font size of the separator)
- **valuedecfontsize**: `NNpx` (Font size of the decimal part of the value)
- **unitfontsize**: `NNpx` (Font size of the unit text)
- **padding**: `NNpx` (Padding size of the tile)
- **width**: `NNpx` (Width of the tile)
- **height**: `NNpx` (Height of the tile)
- **borderradius**: `NNpx` (Border radius size of the tile)
- **bordercolor**: `rgb(20,20,20)` (Color of the border)
- **borderwidth**: `NNpx` (Width of the border)
- **borderstyle**: `solid` (Style of the border)
- **margin**: `NNpx` (Margin between the title/value and the top/bottom)
- **blink**: `int | sep | dec | *` (Makes the integer part, separator, decimal part, or whole value blink on update)
- **style**: `(CSS style for the value)`
- **time**: `duration | date` (Displays duration or date of the value)

## Installation
To install the custom tile widget, follow these steps:

1. Copy the HTML file(s) to `data/customTemplates/dashboard/`.
2. Copy the CSS file to `desktop/custom/`.

## Preset palette
Here is the color palette used for the presets:

![Palette](/img/palette.jpg)


## License

This project is licensed under the MIT License - see the [LICENSE file](/LICENSE) for details.

Feel free to customize and extend the widget as needed to fit your requirements.
If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.
