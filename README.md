# window-control-polybar
displays window names on polybar &amp; lets you minimize, maximize &amp; resize windows.

# add this to your polybar config

```
[module/polywins]
type = custom/script
exec = ~/bin/polywins.sh 2>/dev/null
format = <label>
label = %output%
label-padding = 1
tail = true
```
![pic of OS with polybar](pink-rice.png?raw=true "lol")
