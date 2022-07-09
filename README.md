## Sketchfab Ortographic Viewer
Sketchfab ortographic viewer with presets (left, right, top, etc).
Auto saves the previous UID and zoom values.
## How to use
- Find a model on [Sketchfab](https://sketchfab.com/3d-models/).
- Copy the last part of its link (UID):
  - `sketchfab.com/3d-models/bob-7w7pAfrCfjovwykkEeRFLGw5SXS` -> `7w7pAfrCfjovwykkEeRFLGw5SXS`
- Open [this app](https://k3rielit.github.io/sketchfab/).
- Paste that UID into the textbox at the top.
- Press Reload next to it.
- Change standard views by clicking on the buttons.
  - If some views are inverted, a negative zoom value can fix that.
- Change the zoom with the Zoom textbox.
  - Sometimes there's a zoom limit, keep the Model Inspector (`i`) open to unlock it.
- Don't change the FOV unless it's necessary.
  - If the FOV is set to `0` the viewer may break, then it needs to be refreshed (`Ctrl+R` / `F5`).

With this tool any Sketchfab model can be made into a blueprint:
- Install [Screenshotting](https://chrome.google.com/webstore/detail/full-page-screenshot-capt/pojgkmkfincpdkdgjepkmdekcahmckjp) (Chrome extension)
- Open [Combine images](https://www.quickpicturetools.com/en/combine_images/) (Web app)
- Screenshot the `front`, `rear`, `top`, `side` standard views with the extension, and combine them with the web app.
