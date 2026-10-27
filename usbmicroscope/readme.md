# Scope

A simple full-screen viewer for USB microscopes (such as the Zoomy), running in the browser. It replaces Xploview, which may no longer run on current Macs. This should work on Macs and Chromebooks. Nothing to install.

**Open it:** [https://falkschool.github.io/usbmicroscope/]

## Use

1. Plug in the microscope.
2. Open the link above in **Google Chrome**.
3. Click **Allow** when Chrome asks to use the camera.
4. If you see the laptop's webcam instead of the microscope, pick the microscope from the dropdown at the top.
5. Press **F** or double-click the image for full screen. **Esc** exits.
6. Press **Space** to take a screenshot. It's copied to the clipboard, so you can paste it straight into a doc or slide.

## Controls

| Key | Action |
|-----|--------|
| **F** / double-click | Full screen |
| **Space** | Screenshot: copies the current image to the clipboard (paste into a doc or slide) |
| **M** | Mirror |
| **V** | Flip upside-down |
| **R** | Rotate 90° |

The buttons hide after a couple of seconds. Move the mouse to bring them back.

Copied images are saved at the microscope's full resolution, with any mirror, flip, or rotation applied.

## Troubleshooting

- **Black screen:** unplug the microscope, plug it back in, and reload the page.
- **Camera blocked:** click the camera icon in Chrome's address bar and allow access. On a Mac, also check System Settings → Privacy & Security → Camera and make sure Chrome is on.
- **Wrong camera:** choose the microscope from the dropdown.
- **Space does nothing:** Chrome may need clipboard permission the first time. Click Allow if asked.
- **Chromebooks:** if the camera prompt never appears, camera access may be restricted by school admin settings.

## Notes

- This only shows the live image and copies still frames. It doesn't record video.
- The video stays in your browser. Nothing is uploaded anywhere.
- Chrome is recommended. Other browsers may not behave the same way.
