# FitVids-ie.js
A lightweight, *IE compatible*, easy-to-use jQuery plugin for fluid width video embeds.

FitVids-ie automates [the Intrinsic Ratio Method by Thierry Koblentz](http://www.alistapart.com/articles/creating-intrinsic-ratios-for-video/) to achieve fluid width videos in your responsive web design.

Forked from [davatron5000 FitVids](https://github.com/davatron5000/FitVids.js).

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
