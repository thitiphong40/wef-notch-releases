# wef-notch releases

wef-notch is a small macOS app that turns the MacBook's notch into a panel:
the music playing, your next meeting, a note, a to-do list, a timer, files to
hand on, and what Claude Code is doing.

This is where it is released and updated from. Each Release is a zip under
[**Releases**](https://github.com/thitiphong40/wef-notch-releases/releases),
and the app reads the Feed here (`appcast.xml`, on this repository's Pages)
to find newer ones. A check sends the app's version and nothing else.

To install, download the latest Release's zip, unzip it and drag
`wef-notch.app` into Applications. The app isn't notarized by Apple yet, so
the first time macOS refuses to open it: press **Done**, then **Open Anyway**
in System Settings → Privacy & Security, and open it again. Once only — after
that, wef-notch updates itself.

What it does and how it works:
[the source repository's README](https://github.com/thitiphong40/wef-notch#readme)
(private for now; the steps above are all you need).
