# Calendrical

## What is it?

Calendrical is a plugin for jQuery that provides popup date and time pickers inspired by Google Calender.

## Installation

Copy and include the JavaScript file `jquery.calendrical.js`, and the style sheet `calendrical.css` in your project.

If you use SASS for your project, you can include the code in `calendrical.scss` instead of the css file. If you want to change the color scheme for Calendrical, you can edit the color definitions in the scss file and then regenerate the css using `build_css.sh`.

## Usage

You can add Calendrical date and time pickers to your existing text fields using the following functions:

  * .calendricalDate
  * .calendricalTime
  * .calendricalDateRange
  * .calendricalTimeRange
  * .calendricalDateTimeRange
  
See `example.html` for examples of how to use these functions.

## Options

All of the Calendrical functions can accept an options hash as a parameter.

Available options:

  * __usa__ - Use USA-style middle endian dates (7/21/2010), instead of the default European-style little endian dates (21/7/2010).
  * __isoTime__ - Use 24-hour clock (ISO 8601) instead of default 12 hour clock with am/pm.
  * __defaultHour__ - Default hour to scroll the dropdown time select box to,
  if the field doesn't already have a time value when it's shown. Specify as an integer (0..23). Defaults to 9.
