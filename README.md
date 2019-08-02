# omanshardt/uicCSS
Tiny library with often used css declarations.

**uic-flex.css**
A set of rules that is related to flex-based layouts. I use it a lot for partial parts of a layout to have items easily aligned properly (horizontally and vertically).

**uic-flexy-table.css** is a set of rules that renders tables with the ***flex display model*** rather than with the default ***table layout***. This enables table cells to float according to the available horizontal space and is very appropriate for narrow screens. So this is ideal for the use with media queries, where best practice is to import the css file for the media query in question.
```bash
@import url('uic_flexy_table.css') only screen and (max-width: 750px);
```
This set of rules can be used out of the box but best results were received when it is used with additional  table-specific rules, i.e width and alignment of table content. Also these css rules work best if any table-cell content is wrapped into a span-element that is preceded by a label indicating the property of the respective value.


**uic-griddy-table.css**  is a set of rules that renders tables with the ***grid display model*** rather than with the default ***table layout****. This enables table cells to float according to the available horizontal space and is very appropriate for narrow screens. So this is ideal for the use with media queries, where best practice is to import the css file for the media query in question.
```bash
@import url('uic_flexy_table.css') only screen and (max-width: 750px);
```
These rules add more flexibility in the design of the table layout


Install
-------
```bash
Just download files and link to them as you need.
