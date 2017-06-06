# D3 Brush for Tableau
### Description
If you are bored of the default time range selector, check this out. 

There are just a few thing you have to do, before use it:
* Drag a webpage object on their view with the correct URL. (See the caveat below, but for now the size of this object should be ~975px width and 75px height.)
* Create two parameters
    * “xAxisField” – The name of the Date field to display on the X-Axis (also used for date range filtering).
    * “yAxisField” – The name of the measure to display on the Y-Axis.
* Caveat – This is still fixed in size, with more work it could be built completely responsive, etc. to make it adaptable in any size dashboard vs one that is fixed in size. 

If you want to read more details, check out this blogpost written by Chris DeMartini: http://www.datablick.com/blog/2017/3/2/building-towards-d3js-plugins-for-tableau

### Technical details
To use this vizualization, you have to replace `tableau.server` to your Tableau Server domain
```html
<!-- IMPORTANT! Replace tableau.server to your Tableau server domain -->
<script src="http://tableau.server/javascripts/api/tableau-2.1.1.min.js"></script>
```