# Kindle Clock

A tiny e-ink clock page for a Kindle Paperwhite (7th gen), built to open in the
Kindle's built-in Web Browser.

Shows:

- Big HH:MM digital clock (updates exactly at each minute boundary)
- Weekday and date in Vietnamese
- Vietnamese lunar date with Can-Chi year
- Anti-ghosting: the screen inverts for the first minute of each hour

The clock runs entirely in the browser from the Kindle's own clock, so after
the page loads once it does not need a continuous network connection.

## Use on the Kindle

1. Enable GitHub Pages for this repo (Settings > Pages > Deploy from branch
   `main`, folder `/ (root)`).
2. On the Kindle, open Web Browser and go to the Pages URL.
3. Keep the Kindle from sleeping (see the TESTD_PREVENT_SCREENSAVER trick) if
   you want it as an always-on desk clock.
