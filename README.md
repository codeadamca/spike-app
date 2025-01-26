# LEGO Spike Hub and the App Tools

A Python snippet utilizing the LEGO Spike app class to play sounds on the controlling device, [MicroPython](https://lego.github.io/MINDSTORMS-Robot-Inventor-hub-API/), and a variety of commands: `play_sound()`, `start_sound()`, and `stop_sound()`.

## Sample Code 

```py
from mindstorms import MSHub, App
from mindstorms.control import wait_for_seconds

hub = MSHub()

app = App()

app.play_sound('Robot 1')
app.play_sound('Suction Cup')
app.play_sound('Train On Tracks')

app.start_sound('Service Announcement')

wait_for_seconds(0.5)

app.stop_sound()

hub.speaker.beep()
```

***

## Repo Resources

* [Visual Studio Code](https://code.visualstudio.com/)
* [MicroPython for LEGO Robot Inventor](https://www.lego.com/en-ca/themes/mindstorms/downloads)
* [LEGO Mindstorms](https://www.lego.com/en-ca/themes/mindstorms)
* [LEGO Mindstorms App for Mac](https://apps.apple.com/us/app/lego-mindstorms-inventor/id1515448947)
* [LEGO Mindstorms App for Android](https://play.google.com/store/apps/details?id=com.lego.retail.mindstorms)
* [LEGO Mindstorms App for Windows](https://www.microsoft.com/store/apps/9N7GN3KC2GK6)

<br>
<a href="https://codeadam.ca">
<img src="https://cdn.codeadam.ca/images@1.0.0/codeadam-logo-coloured-horizontal.png" width="200">
</a>
