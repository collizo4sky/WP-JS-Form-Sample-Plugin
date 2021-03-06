![standard field types](https://raw.githubusercontent.com/danieliser/WP-JS-Form-Sample-Plugin/master/screenshots/3.png)

Having built many interfaces in WordPress over the past 7 years I recently built this as a quick start to any project when admin forms are needed. It is built mostly in JavaScript but fields are easily passed from PHP as in this example. Features are too many to name but include:

- Easy form / settings management. Add fields with a few extra lines in an array.
- If you already manage fields in an array (EDD, Popup Maker) you can easily port to this new rendering method.
- Lots of powerful custom fields including post type search fields, link pickers, license keys, color pickers, rangesliders and even a boolean based targerting/conditions manager.
- Includes modal forms that also allow tab/subtab combinations (example coming soon). These are generated on the fly from the same types of field arrays as this form.
- Field dependency management, inline documentation and great default styles mean you spend less time crafting forms and more time creating awesome features.
- Also included is a simple to use Options class for storing and retrieving your settings in single wp_option row. Though this interface can easily be manipulated for post meta boxes as well.

## Tabbed Forms

Besides offering field management, this library offers multiple variations of tabs, subtabs and sections to organize your forms.

- Tabs and Subtabs can be set as vertical, horizontal or link tabs.
- Styled to match the WordPress Admin interface, but can easily be customized to match your existing setup.
- Forms can be organized with just fields, tabs of fields or tabs of subtabs of fields etc.


## Credits

This is the culmination of work put in over the last year to build or rebuild the interfaces of several plugins including:

- [@daniel_iser](https://twitter.com/daniel_iser)
- Popup Maker
- Ahoy!