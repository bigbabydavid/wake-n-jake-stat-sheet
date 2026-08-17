# Wake N Jake Stat Sheet

OBS lower-third stat graphics driven by the live MLB Stats API.

- Control panel: https://bigbabydavid.github.io/wake-n-jake-stat-sheet/
- OBS Browser Source (1920x1080): https://bigbabydavid.github.io/wake-n-jake-stat-sheet/?display=1

The control panel and the OBS display sync through a dedicated Firebase Realtime Database
(project: wnj-lowerthird), which is what lets the graphic reach OBS's separate browser process.
A plain HTTPS poll runs alongside the realtime socket as a fallback.
