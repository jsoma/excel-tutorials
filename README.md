* [Rodent infestations](pivot-tables-rats/) (guided)
* [Motor vehicle crashes](pivot-tables-crashes/) (less guidance)
* [Character encoding](encoding/)
* [Row limits](row-limits/)
* [Issues with data types](data-types/)

## Video to gif conversion script

Just keeping this here so I know how I made all the gifs!

```bash
ffmpeg -y -i export-csv.mov -vf palettegen palette.png && \
ffmpeg -y -i export-csv.mov -i palette.png -f gif \
    -filter_complex "fps=10, scale=-1:400, paletteuse=dither=none" \
    - | \
gifsicle -O3 -o export-csv.gif && \
rm palette.png
```