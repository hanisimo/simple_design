# simple_design  (Null Safety Version)

A simple design library for Flutter.

## :sparkles: What's New
- Null Safety Support.
- Update the deprecated codes to the latest version.
- Update the package version to 1.0.4.

## This package includes:
- Premade themes, dark and light brightness
- Several custom Simple Design widgets, serving the original design idea.

For general design advice I used the Material Design Specifications from material.io.

## Font

I recommend using the free-for-commercial font "HK Grotesk", which is used in the example
and also defined as the standart font in the themes.

But really and sans-serif, geometric or grotesk typeface should work well (for example 
Lineto Circular).

## SDAppBar and SDSliverAppBar

These two widgets are meant to be used instead of the regular AppBar/SliverAppBar.
They use certain styling that otherwise would have to be applied to every AppBar in
your app.

They are customizable with title, leading, actions, bottom, automaticallyImplyLeading
and flexibeSpace. The other values are not customizable to not negatively impact the
appearance of your app.

## SDDialog with SDDismissButton and SDActionButton

This is a custom dialog and should be used in the showDialog() method instead of
AlertDialog or SimpleDialog. It can be given values for title, content, a SDDismissButton
for a dismiss button, a SDActionButton for an action button and a bool barrierDismissable,
which is not yet working.

The SDDismissButton and SDActionButton should be self-explaining.

## SDDivider and SDSectionHeader

Designed for the use in Colums and Lists, the SDDivider provides a vertical padding of 36.0
pixels, which is recommended, but can be customized with the height property.

The SDSectionHeader is to be used below a SDDivider to announce the title of a new section,
as it can be seen in the example application.

## SDCard

The SDCard widget is a highly customizable card, with options for mediaContent, content, title,
subtitle, actions and backgroundColor. It has a slight shadow underneath and is best used in
Colums and Lists.
