# Simple Percentage Grid v1.0

Grid frameworks are generally way too bloated. This is a simple 12 column grid initially based off of 960px with 20px gutters that has been converted to percentages. So, it works in any new or pre-existing layout, of all sizes.

##All You Need in 16 Lines of CSS

```css
.row { clear: both; }
.row:before, .row:after {content: " "; display: table; } .row:after { clear: both; } /*clearfix*/
.row .column  { padding-left: 1.041666666%; padding-right: 1.041666666%; /*gutter*/ float: left; }
.row .column.right  { float: right; /*good for asides that skip column(s) for extra spacing*/ }
.row .one { width: 6.25%; }
.row .two { width: 14.583333333%; }
.row .three { width: 22.916666666%; }
.row .four { width: 31.25%; }
.row .five { width: 39.583333333%; }
.row .six { width: 47.916666666%; }
.row .seven { width: 56.25%; }
.row .eight { width: 64.583333333%; }
.row .nine { width: 72.916666666%; }
.row .ten { width: 81.25%; }
.row .eleven { width: 89.583333333%; }
.row .twelve { width: 97.916666666%; }
```

##Basic HTML Markup

```html
<div class="row">
 <div class="column eight">Eight Columns</div>
 <div class="column four">Four Columns</div>
</div>
```

##Demo

http://robspangler.com/git/css-simple-percentage-grid/demo.html

## Changelog

### Version 1.0 (2/26/2014)
* Initial release

## Author

Robert Spangler

* http://www.robspangler.com
* https://twitter.com/robertspangler
* http://www.linkedin.com/in/robertspangler