## hex <-> rgb converter
rgb can be input as: <br>
 ,,50 -> 0,0,50 <br>
 100 30 60 -> 100, 30, 60 <br>
 20 -> 20, 0, 0 <br>

## color proportions
the site calculates what happened to the first color when you give it the resulting second color, and can then apply that difference to whatever third color you give it. <br>
there are 6 modes right now: <br>
per channel percentile and absolute (rgb) <br>
absolute and relative difference (oklch) <br>
oklch hue shift <br> 
oklch lightness and chroma <br>

## good contributions:
make rgb input in color proportions accept input types the same way the converter does (like ,,50) <br>
add a hex result copy field in color proportions <br>
add other color formats in the converter <br>
dark mode <br>
disable-able ',' and '#' in copy (and input) fields <br>
