
<p align="center">
  <img width="200" height="200" src="https://github.com/Mark2Mark/variable-font-preview/blob/master/Variable%20Font%20Preview%20X.glyphsReporter/Contents/Resources/VFP-Icon.png">
</p>

# Variable Font Preview 3

The famous plugin now available for Glyphs 3 with piles of improvements and new features.

## Highlights:

- You can now download it directly from the Plugin Manager right inside of GlyphsApp.
- No axes limit.
- Magnifier: Click into the preview to show/close. Hold `cmd` key while moving the mouse to reposition.
- Measurement of interpolation: Select 2 nodes to measure horizontal and vertical distance as well as the angle.
- Standalone window: Choose between the preview inside of the Edit Tab or as a window. YOu can put that on another screen.
- More compact sliders: cleaner UI, less finger fatigue.
- Choose to round values or use floats.
- Percentage bars for masters involvements.
- 

## TODO

- [ ] Re-enable RTL


## Changelog

### v3.0.0

- Fix instances don’t show *all* the time in the Menu.
- Quit plugin on window close button.
- Measure between 2 selected nodes.
  - And: measure Width & Height, too.
  - And center measurement if `Center Preview` is active.
- Don’t hide window in Exposé.
- Fix bug: wrong preference saving key that connected "centerPreviewGlyph" with "linkToSelectedMaster".
- Show Percentage Bars for Involved Masters.
- Improve nodes drawing: show tangents of oncurve nodes.
- Hidden flag to customize Layer Background Colors for Fill and Outline.
- Higher contrast for background colors.
- Fix: Update menu instances right after adding an instance.
- Smooth standalone window fade, improve window behaviour to be never a main window.
- Implement plugin manager purchase & offer trial version.
• New Feature: Magnifier. Click in view to show/hide, `cmd` + move mouse to reposition.
• Implement new layer shapes API.
• minimum height for preview in EditTab. It cannot collapse anymore, which lead to some confusion. Thanks Minjoo!
• New Feature: User choice to use rounded or decimal values with sliders.
