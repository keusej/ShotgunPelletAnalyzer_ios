# Shotgun Pellet Analyzer

Shotgun Pellet Analyzer is an iOS app for reviewing shotgun pattern photos and estimating pellet distribution inside a standard 30-inch pattern circle.

The app is designed for shooters who want a practical field tool for pattern testing. Select a pattern photo from your photo library, run automatic pellet detection, adjust the results when needed, and save a marked-up image with the pellet counts included.

## What It Does

- Detects pellet strikes in shotgun pattern photos
- Counts pellets inside the 30-inch pattern circle
- Reports pellets inside the 10-inch core
- Supports manual add/remove correction after detection
- Lets you zoom and pan for detailed review
- Saves an annotated image back to your photo library
- Supports an optional shell pellet count for percentage calculations

## Using the App

1. Tap the **folder** button and select a pattern photo from your photo library.
2. If the image includes extra background, tap the **dashed rectangle** button and draw a search region around the target paper, calibration line, and pellet pattern. Drag the box or its corners to adjust it.
3. Tap the **sliders** button to choose the detection mode and settings.
4. Tap the **crosshair** button to detect pellets.
5. Pinch to zoom and drag to pan while reviewing.
6. Tap to add a missed pellet. Double-tap or long-press near a marker to remove it.
7. Tap **save** to export a marked image with counts and percentages.

### Toolbar Guide

- **Folder**: open a new image.
- **Sliders**: detector settings.
- **Dashed rectangle**: draw or edit the search region.
- **Rectangle with X**: clear the search region.
- **Trash**: clear pellet markers.
- **Crosshair**: run automatic detection.
- **Plus / minus circles**: adjust marker dot size.
- **Save**: save the annotated image.
- **Waveform**: save a detector heatmap for troubleshooting.

### Detector Settings

- **Find circle from line**: use a straight calibration line on the target to estimate scale, then place the 30-inch analysis circle around the densest pellet region.
- **Use drawn 30in circle**: use a visible 30-inch circle already drawn on the target.
- **Length of line (inches)**: enter the real length of the calibration line, commonly 12 inches.
- **Pellet sensitivity**: increase if real pellet holes are missed, decrease if folds or marks are falsely detected.
- **Pellets in shell**: optional total pellet count; when set, the app reports percentages for the 30-inch pattern and 10-inch core.

## Screenshots

<table>
  <tr>
    <td align="center" width="33%">
      <img src="Images/screenshots/app-home.png" alt="Shotgun Pellet Analyzer home screen" width="220">
      <br>
      <strong>Select a Pattern</strong>
    </td>
    <td align="center" width="33%">
      <img src="Images/screenshots/detector-settings.png" alt="Auto-detector settings with calibration line mode" width="220">
      <br>
      <strong>Detector Settings</strong>
    </td>
    <td align="center" width="33%">
      <img src="Images/screenshots/pattern-detected.png" alt="Line-calibrated shotgun pattern with detected pellet strikes" width="220">
      <br>
      <strong>Automatic Detection</strong>
    </td>
  </tr>
</table>

## Getting Started With Patterns

New to shotgun patterning, or want cleaner app results?

[Getting Started With Shotgun Patterns](getting-started-with-shotgun-patterns.md) covers useful equipment, calibration lines, optional 30-inch circles, lighting, and photo tips.

## Support

For questions, bug reports, or feature requests, open an issue in this repository:

[Shotgun Pellet Analyzer Support Issues](https://github.com/keusej/ShotgunPelletAnalyzer_ios/issues)

When reporting a detection issue, it helps to include:

- The app version
- The iPhone or iPad model
- Whether the target was paper or cardboard
- A description of what was missed or falsely detected

Please avoid posting sensitive personal information in public issues.

## Privacy

Shotgun Pellet Analyzer processes selected images locally on your device. It does not create accounts, upload photos, collect personal information, track users, or use advertising.

[Privacy Policy](PRIVACY.md)
