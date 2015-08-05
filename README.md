# Simple Percentage Grid v1.0

Grid frameworks are generally way too bloated. This is a simple 12 column grid initially based off of 960px with 20px gutters that has been converted to percentages. So, it works in any new or pre-existing layout, of all sizes.

##All You Need in 16 Lines of CSS

```css
.row { clear: both; }
.row:before, .row:after {content: " "; display: table; } .row:after { clear: both; } /*clearfix*/
.row .column  { padding-left: 20px; padding-right: 20px; /*gutter*/ float: left; }
.row .column.right  { float: right; /*good for asides that skip column(s) for extra spacing*/ }
.row .one { width: 8.333333333%; }
.row .two { width: 16.666666666%; }
.row .three { width: 25%; }
.row .four { width: 33.333333333%; }
.row .five { width: 41.666666666%; }
.row .six { width: 50%; }
.row .seven { width: 58.333333333; }
.row .eight { width: 66.666666666%; }
.row .nine { width: 75%; }
.row .ten { width: 83.333333333%; }
.row .eleven { width: 91.666666666%; }
.row .twelve { width: 100%; }
```

##Basic HTML Markup

```html
<div class="row">
 <div class="column eight">Eight Columns</div>
 <div class="column four">Four Columns</div>
</div>
```

##Demo

http://robspangler.com/git/css-simple-percentage-grid/demo-border-box.html

## Changelog

### Version 2.0 (2/26/2014)
* Converted to "border-box" box-sizing (see: http://www.paulirish.com/2012/box-sizing-border-box-ftw/)
* Legacy "content-box" preserved

### Version 1.0 (2/26/2014)
* Initial release

## Author

Robert Spangler

* http://www.robspangler.com
* https://twitter.com/robertspangler
* http://www.linkedin.com/in/robertspangler