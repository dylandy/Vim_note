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
##移動游標後直接進入編輯模式

*  移動到本行最後一個字元，再進入編輯模式 `A`

##移動游標
1. 上 
`k`
2. 下 
`j`
3. 左 
`h`
4. 右 
`l`
