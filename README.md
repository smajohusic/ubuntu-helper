## Display

You can set the current display that is used by running:

`export DISPLAY=:0`

`xset q`

After that you can turn on or of the display

`xset dpms force off`

`xset dpms force on`

You can also create a script that disables screensaver and screen blanking:

```script
#!/bin/sh
export DISPLAY=:0.0
xset s off
xset s noblank
xset -dpms
```
