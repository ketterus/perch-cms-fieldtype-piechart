# perch-cms-fieldtype-piechart

Piechart fieldtype for [Perch CMS](http://grabaperch.com).

**This README document is a work in progress.**

## Installation

Download and place the `simona_piechart` folder within `perch/addons/fieldtypes`.

## Usage

Once installed, the fieldtype can be used in a template by setting the `type` attribute to `simona_piechart`:

`<perch:content id="piechart" type="simona_piechart" label="Pie Chart" title="true" />`

**TODO:** An example basic template is supplied in the `templates` folder.

### TODO: Attributes

**width**
Set the width attribute to control the width of the output chart (default: `460px`). Example: `width="300px"`.

**height**
Set the height attribute to control the height of the output chart (default: `320px`). Example: `height="300px"`.

## Credits

* handsontable: http://handsontable.com/

## License

perch-cms-fieldtype-piechart is released under the [MIT License](https://github.com/siansell/perch-cms-fieldtype-piechart/blob/master/LICENSE).