# Structure of a paint layout

Paint layouts are not single template files. They are more like a bundle of settings and templates that can react to multiple scenarios. It is pretty straightforward to create one paint layout that controls how many different assets are displayed.

It's important to realise that other things can be placed inside the paint layout bundle too, such as asset lists or even other paint layouts.

## Standard

A standard paint layout looks like this:

* Paint layout container
  * Page Contents (a wrapper for all type formats in the paint layout)
  * Type formats
    * Default format (the template that will be used to display all asset types)

## Complex

A more complex paint layout might look like this:

* Paint layout container
  * Page Contents
  * Type formats
    * Default format
    * Data record format (a different template for use when displaying data records)
    * Asset listing page format (a different template for use when displaying asset lists)
  * A child paint layout (another paint layout inside this one)
  * A helper asset listing page (an asset list inside the paint layout bundle)
