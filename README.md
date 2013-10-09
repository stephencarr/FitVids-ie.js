# FitVids-ie.js
A lightweight, *IE9 compatible*, easy-to-use jQuery plugin for fluid width video embeds.

FitVids-ie automates [the Intrinsic Ratio Method by Thierry Koblentz](http://www.alistapart.com/articles/creating-intrinsic-ratios-for-video/) to achieve fluid width videos in your responsive web design.

## Explanation

This fluid width video plugin (forked from [davatron5000 FitVids](https://github.com/davatron5000/FitVids.js)) is an attempt to overcome a problem found in IE9 where using `.wrap()` on an iFrame causes an error. 

The problem is explained in this FitVids issue: https://github.com/davatron5000/FitVids.js/issues/26

More information can be found here: http://msdn.microsoft.com/en-us/library/gg622929%28v=VS.85%29.aspx

## Usage

Setup is as per the original plugin with the subtle extra requirement that each video should be wrapped in an individual div which fitvids will target.

```html
<div class="myvideo">
  <iframe width="420" height="315" src="//www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
</div>
<div class="myvideo">
  <iframe width="420" height="315" src="//www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
</div>
```

```javascript
$(".myvideo").fitVids();
```

## Credits
@ChrisCoyier, @davatron5000, @TrentWalton, @raygunray, @stephencarr
