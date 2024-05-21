# Yet Another Awesome Go Gui

**only packages without html, webkit, js, etc**

| Package | SSE Size, kb | ~SSE Cpu usage, % | Comment |
|---------|--------------|--------------------|---------|
| Fyne | 26595 | 0.75 | go.sum too big: 666 lines, bad API for keyboard events (try to create a program with response on Shift+Ins) |
| giu | 14122 | 0.3 |    |
| ebiten | 10210 | 3.2 |    |
| pixel | 3717 | 3.0 |    |
| shiny | 3623 | 0 | it is not possible to dynamically change the window title, absent API for dialogs, on windows "Ins" key is Unknown, no long key press reaction |
| gio | 9965 | 0 | Not trivial API, absent key "Insert" in keyboard API |
| goey | 2855 | 0 |   |

SSE - some simplest example (with static graphic)

CPU usage when nothing doing
