## Texas Advanced Computing Center
# Django CMS Plugin: "Offset"

This plugin offsets the content of nested plugin instances from surrounding content.

- __`__dist-name__`__: `djangocms-tacc-offset`
- __`__package_name__`__: `djangocms_tacc_offset`
- __`__ClassName__`__: `TaccsiteOffset`
- __"Plugin Name"__: "Offset Content"

## Quick Start

1. Follow https://github.com/tacc-wbomar/Core-CMS-Plugin/wiki/Core-CMS-Plugin-Usage-Quick-Start.

## Usage

1. Add instance of plugin to a page.
1. Configure the plugin instance.
1. Nest any plugin instance(s) inside it.
1. See plugin render nested plugin offset from surrounding content.

## Features

- Wraps plugin instances in an `<aside>`.
- Offsets nested content in the direction configured.

## Caveats

1. The provided styles are only a sample and are not suitable for all designs.

  _Your app should override the template or stylesheet to load its own styles._
