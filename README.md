##Modes

1. insert mode -> insert texts
2. command mode -> edit file likes "copy, delete, move ..." 
3. normal mode -> usually started with ":"

##Often use mode changing commands

* To enter command mode or normal mode

```
1. `ESC`
2. `ctrl + [`
```

* To enter insert mode
  * Append :
    * `a` : insert text into next location.
    * `A` : insert text into the last location in current line.
  * Insert : 
    * `i` : insert text into previous location. 
    * `I` : insert text into the first location in current line.
  * Open a new line:
    * `o` : open a new line (next line).
    * `O` : open a new line (previous line).
        

##Moving cursor
* `k` : cursor up
* `j` : cursor down
* `h` : cursor left
* `l` : cursor right
* `[numbers]` + `[k , j , h , l]` : move cursor to how many alphabets somewhere.
* `H` : move cursor to the first line of current viewing spaces.
* `M` : move cursor to the middle of current viewing spaces.
* `L` : move cursor to the last line of current viewing spaces.
* `G` : move cursor to the last line of current document.
* `gg` : move cursor to the first line of current document.
* `b` : move cursor to previous word.
* `w` : move cursor to next word.
* `^` : move cursor to the first alphabet of current line.
* `$` : move cursor to the last alphabet of current line.
* `[numbers]` + `[G , gg]` : move cursor to particular line.

##File Zipping
* `zo` : open current zipped text block.
* `zc` : zip up current text block.
* `zm` : zip all the text block in current document.

