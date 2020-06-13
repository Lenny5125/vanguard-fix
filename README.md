# vanguard-fix
 This is a simple fix for the "We couldn't install a required dependency. Please try again, restart your computer or reach out to us at Riot Support" Error.
# How to use it
 Simply run "fixvalorant.bat" as Administrator and try to launch Valorant again.
# How does it work?
```batch
sc delete vgc
sc delete vgk
sc stop vgk
```