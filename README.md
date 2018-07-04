# CSS Grids and IE

This repo is a simple responsive three column layout so that I can practice supporting IE while using CSS Grids with browsers that support it.

The technique used to create a 3-column layout in IE is based on a [CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/CSS_Grid_and_Progressive_Enhancement) article that goes into detail about IE support with CSS Grids.

## @supports

I am using [@supports](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports) to target browsers that support CSS Grids.  However, IE does not support *@supports*, but by targeting IE first, I can apply any *@supports* to browsers that support Grids and @supports.