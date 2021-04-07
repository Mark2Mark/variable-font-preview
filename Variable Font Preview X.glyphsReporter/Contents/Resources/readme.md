/**
 UI:
 2.2 build 3 (aka VFP 2020)
 + I changed some of the window behaviours as you reported.
	 + It tires to redraw itself when the window is moved to another monitor, *hopefully* eliminating those weird resizing bugs?
	 + When the window is on another monitor and GlyphsApp loses focus, it stays around = better UX
	 + Closing the window will shut down the plugin
 + Interpolated measurement between 2 selected nodes. AND: measure Width & Height, too.
 + The Instances in the Menu show up again now.
 + Supports down to MacOS 10.12 by default now
 + Force centering the "Make Instance:" Dialogue Panel
 2.1 build 2 (aka VFP 2020)
 + New Feature: Undock the preview into a standalone window. BIGGIEE!
 + New Feature: BOTH Previews got the context menu too, now. Not only the
   sliderbox. Less fiddly targeting with the right click.
	 + And hopefully some users’ issues with not being able to get the context menu are passé now.
 2.0
 + New Feature: Virtual Master Support
 + New Feature: Option to center drawn glyph
 + New Feature: Enter your values in the Slider Label. Change Values with Arrow Keys (Shift/Cmd+Shift for 10/100 steps)
 + You can extrapolate through doing so, the label text will color to indicate that an extrapolation is happening
 + Streamlined UI:
 	+ Only sliders for the existing axes are shown. Give you more space in your edit view
 	+ Buttons are now hidden and reformed into a right click context menu. You won't access to them too often, so that declutters the panel
 + Panel doesn't detach from window anymore when the caret is at the end of a line. (However it will still fail to live update the preview in that caes, due to the Glyphs API)
 + New Feature: Nodes in preferences size
 + New Feature: Display involved Masters (Beta)
 + New Feature: Dial in any of your font’s instances
 + New Feature: Right-To-Left Support (Beta)
 + BugFix: Update Sliders on Axes change
 + BugFix: Update Sliders on Axes Values Change (in Master settigns)
*/

#pragma mark - Bugs
 /**
  * [     ] GlyphsApp redrawing (e.g. toggle Show Background or Bounds) causes sliders to reset to 0
  * [     ] If you change tab content (text), dont scroll after that and move a slider: the preview content disappears, and reappears only once you scroll and ove the slider again.
  * [     ] Deactivating and activating shows the preview and slider immediately in Loris' font, but not in DunkelSans Condensed.
  * [FIXED] On Tab change, the slider values are always reset to 0, on font change not, though.
  * [     ] ONLY ctrl + left click doesn’t call the Menu to open. 2 finger Tap and right click work.
  * [FIXED] The multiple instances of the Menu dont share the same button states.
 */

#pragma mark - TODOs
/**
 * --- See Notion.
 */
