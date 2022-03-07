
<p align="center">
  <img width="200" height="200" src="https://github.com/Mark2Mark/variable-font-preview/blob/main/.images/VFP-Icon.png">
</p>

# Variable Font Preview 3

The famous plugin now available for Glyphs 3 with piles of improvements and new features.

💡 Minimum Glyphs version: build <code>3062</code>.

⚠️ Do not download directly from here. Please install via GlyphsApp’s Plugin Manager ⚠️


&nbsp;
## Highlights

- You can now download it directly from the Plugin Manager right inside of GlyphsApp.
- No axes limit.
- Magnifier: Click into the preview to show/close. Hold <kbd>⌘</kbd>`(command)` key while moving the mouse to reposition.
- Measurement of interpolation: Select 2 nodes to measure horizontal and vertical distance as well as the angle.
- Standalone window: Choose between the preview inside of the Edit Tab or as a window. YOu can put that on another screen.
- More compact sliders: cleaner UI, less finger fatigue.
- Choose to round values or use floats.
- Percentage bars for masters involvements.
- Updates will load automatically. You will never have to manually install any updates anymore.
- Keybobard shortcut to (de-)activate plugin: <kbd>⌃⌥⌘V</kbd>

&nbsp;
## Todo

- Currently there is a know issue, where Variable Font Preview behaves a bit odd, when the Red Arrows plugin is also active. In that case, deactivate Red Arrows. If that improves behaviour, please let me know. We are investigating the cause.
- Right now I am improving the handling of more than one fonts. This is something, Variable Font Preview can’t do yet, but very soon it will.
- For more, see [issues](https://github.com/Mark2Mark/variable-font-preview/issues)

&nbsp;
## Changelog

<details><summary>Expand if you’re curious.</summary>

3.2.2
-----

Fix
- fix a case where the preview did not show.


3.2.1
-----

New
- Update sliders when font axes are added or removed.  
  When changing the *axes location of a master*, the sliders don’t update yet, as this is more tricky to implement. For now, just disable and enable the plugin for that to take effect.


3.2.0
-----

New
- Hovering over the instances in the menu applies the instance preview right away.


3.1.0
-----

New
- Sliders remember their positions now when switching fonts.
- Radar Chart for Master Mapping.
- Option to center Preview Glyph.

Changes
- Don’t move window by dragging anywhere in the view.

Fix
- Standalone window only persist over any other app, when the setting for that is active.  
  This wasn’t properly working before. The user had to check and uncheck the setting before it did what it claimed to do.
- Prevent window flashing when switching font documents.  
  Very convenient when having the standalone window large on a second monitor
- Draw only in foremost font.
- Deal with multiple open fonts now.
- Avoid preview padding to shrink below minimum size.
- Improve sliderbox position for some users which was partially hidden in some cases.  
  Also fixes that the previewBox showed up together with the standalone when standalone window was enabled and glyphs was launched

Other
- Add some left padding to the preview window.
- Cleanup.
- Semi-fix: use corner components.


3.0.5
-----

- New feature: Option to hide current layer foreground. Make the preview shine in all its glory.

3.0.4
-----

- New feature: "Always On Top" If active it shows the window on top of other windows even if GlyphsApp is in the background. Useful depending on if you use multiple screens or not.
- New feature: Slider now have tickmarks if the range is smaller than 11. Useful for for italic axis, where there are only 0 and 1 as values.

3.0.3
-----

- Remove debug logging

3.0.2
-----

- Fix Registry issue.

3.0.1
-----

- Add menu item "Open Registration Window"

3.0.0
-----

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
- New Feature: Magnifier. Click in view to show/hide, `cmd` + move mouse to reposition. 
- Implement new layer shapes API. 
- Minimum height for preview in EditTab. It cannot collapse anymore, which lead to some confusion. Thanks Minjoo! 
- New Feature: User choice to use rounded or decimal values with sliders. 
</details>

&nbsp;
## FAQ
<details><summary>🙋 I can’t find it in the Plugin Manager.</summary>
➡️ You need to check if your GlyphsApp build is higher than <code>3062</code>.  
If Glyphs doesn’t offer you a high enough version, enable activate GlyphsApp <code>Preferences</code> > <code>"Updates"</code> > <code>“Show cutting edge versions”</code>. Note: you can have several GlyphsApp versions
</details>

&nbsp;
## How to activate your license<a id="how-to-activate-your-license"></a>  
After your purchase, the license key should be set automatically for you. If it isn’t:  
<details><summary>Activating the plugin is easy, just follow the simple steps [click to open]</summary>
<ol>
  <li>👉 Make sure you have GlyphsApp 3 build <code>3062</code> or higher.</li>
  <li>👉 If you haven't already, download the plugin directly in the GlyphsApp Plugin Manager and restart GlyphsApp once.</li>
  <li>👉 When you activate the plugin, you'll be prompted with a window*, click the <code>"Enter License"</code> button.</li>
  <li>👉 On the screen that opens enter your Email address, and the license code from your Email.</li>
  <li>👉 When you've completed the above, just click the <code>"Activate License"</code> button. Within a few seconds your product should be activated for full use!</li>
</ol>

*) If the window doesn’t show, you can right-click into the Edit Tab (that’s the window where you do your drawings) and in the context menu click <code>"Purchase Variable Font Preview 3"</code>. Alternatively you can right click into the plugin’s Preview box and click <code>"Open Registration Window"</code>.
</details>

&nbsp;
## How to enter a coupon
<details><summary>If you have a coupon, follow these steps to use it for a discount on your purchase [click to open]</summary>
<ol>
  <li>👉 Make sure you have GlyphsApp 3 build <code>3062</code> or higher.</li>
  <li>👉 If you haven't already, download the plugin directly in the GlyphsApp Plugin Manager and restart GlyphsApp once.</li>
  <li>👉 When you activate the plugin, you'll be prompted with a window*, click the <code>"Buy Now"</code> button.</li>
  <li>👉 On the screen that opens enter your Email address, and click <code>»Continue«</code>.</li>
  <li>👉 Follow the form until it asks you to pay. But now click <code>»Add Coupon«</code> and then continue to pay.</li>
  <li>👉 On success you should get an Email with a licence code.</li>
  <li>👉 Use that to activate your license <a href="#how-to-activate-your-license"> (steps here).</a> </li>
</ol>

⚠️ Note: The Coupon is **not** the License Code. Please don’t enter the Coupon Code into the field for your License Code!

*) If the window doesn’t show, you can right-click into the Edit Tab (that’s the window where you do your drawings) and in the context menu click <code>"Purchase Variable Font Preview 3"</code>. Alternatively you can right click into the plugin’s Preview box and click <code>"Open Registration Window"</code>.

If you can’t see the <code>»Add Coupon«</code>, that’s likely to a reported GlyphsApp bug, switching to Dark Mode and opening the window again might solve it.
</details>

&nbsp;

---

<p align="center">
  <img src="https://github.com/Mark2Mark/variable-font-preview/blob/main/.images/Plugin%20Manager%20-%20Variable%20Font%20Preview.jpg?raw=true">
</p>
