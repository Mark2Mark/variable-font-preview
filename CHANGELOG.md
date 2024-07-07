# Changelog

## 3.7.6

2024-07-04

### Fix

* In some cases the involved masters flickered between a dashed and solid outline

## 3.7.5

2024-07-04

### New

* **UI**: Use Custom Parameter "Preview Ascender/Descender" to adjust preview scale

    With this you can see your drawings that exceed the standard extender heights now

## 3.7.4

2024-07-03

### Fix

* Instances now properly dial in every time

    In cases where instances had any axis value as 0, those did not show properly. Also variable exports are not shown in the list anymore.
    Public [#30](https://github.com/Mark2Mark/variable-font-preview/issues/30) 

## 3.7.3

2024-07-03

### Changes

* **UI**: Animation controls look nicer now

## 3.7.2

2024-07-02

### Changes

* **UI**: Show masters radar chart always when "Draw In Edit View" is on

    Before, also "Show Involved Masters" had to be on.

## 3.7.1

2024-07-02

* Small changes under the hood

## 3.7

2024-07-02

### New

* **UI**: Show CPU usage when animation is on

* **UI**: Speed selector for slider animations

* **UI**: Slider animation (beta)

### Changes

* **UI**: Add animation timing functions (not yet accessible via UI)

## 3.6.0

2024-03-05

### New

* **UI**: Variation default will be now shown when plugin starts with a font

    Before all sliders where set to 0 and the preview could look strangely extrapolated.

### Changes

* **UI**: Fix recognition of virtual masters

    Even if a font has only one master and otherwise only virtual masters, their axes will be now detected

## 3.5.6

2023-12-18

### Changes

* Improve MIDI handling

## 3.5.5

2023-11-27

### Fix

* Center palette color layers, too ...

    ... given that the associated master layer is not a color layer

* Prevent a crash when adding new axis

* More color layer improvements

## 3.5.4

2023-11-23

### Fix

* Slightly improve color fonts rendering: COLRv1 shows only the color layer now.

## 3.5.3

2023-11-20

### Changes

* Put deployment target down to 10.14

## 3.5.2

2023-11-20

### Changes

* Bypass more stuff in release build

## 3.5.1

2023-11-17

* Small changes under the hood

## 3.5.0

2023-11-17

* Small changes under the hood

## 3.4.9

2023-06-08

### Fix

* **UI**: Show current line works now again also in newer Glyphs versions

* **UI**: Keep preview box shadow the same for both font modes

    Switching is now less obstrusive

## 3.4.8

2023-05-31

### Changes

* **UI**: Slider box is a little narrower now. Generally more comfortable, as les movement is required. For fine tuning, use the slider value text fields and arrow keys.

* **UI**: Slider box looks now more modern and is better visible in all color modes (dark, light) and when over text

## 3.4.7

2023-05-31

### Changes

* **UI**: Improve menu tooltips

## 3.4.6

2023-05-23

### Changes

* **UI**: Magnifier is now relative to preview size. The bigger the preview, the bigger the magnification. You can now inspect the tiniest details/

## 3.4.5

2023-05-23

### Fix

* **UI**: Preview only current layer: now also in the standalone window.

    Closes public [#17](https://github.com/Mark2Mark/variable-font-preview/issues/17) 

## 3.4.4

2023-05-20

### Changes

* **UI**: Another attempt to fix an issue where some users encountered different scales of the preview when moving windows to other screens

## 3.4.3

2023-05-17

### Changes

* **UI**: Attempt to fix an issue where some users encountered different scales of the preview when moving windows to other screens

    As I cannot reproduce the problem, this fix is blindly implemented and I need feedback from these users if it is really fixed.

    MAYBE closes #4 and closes #9

### Fix

* **UI**: Support other UPMs than 1000

    Preview scale is now always the same no matter which UPM the font has

    Closes #20

## 3.4.2

2023-05-17

### New

* Involved Masters Charts now only show when "Show Involved Masters" is enabled. Cleans up the Edit View if desired.

    Also renamed Menu Item "Draw in Active Layer" → "Draw in Edit View"

* **UI**: Allow tabbing through the text fields (actual commit)

## 3.4.1

2023-05-17

### New

* **UI**: Allow tabbing through the text fields

## 3.4.0

2023-05-17

* Small changes under the hood

## 3.3.11

2023-05-10

### New

* **UI**: Show only current line from EditView

### Changes

* **UI**: Distinguish Live Font from drawn text via slightly different background color

### Fix

* **UI**: Show preview and sliders on tab change (always)

    Closes #17

## 3.3.6

2022-05-10

### New

* Disconnect preview size from built-in bottom preview

    Often requested feature.

### Changes

* Lay out masters in radar chart clock wise (opposite direction of before)

* Radar chart: draw master label in bold when selected

### Fix

* "Draw in Active Layer" turned off makes the radar chart fill color all black

    Closes #7

* Improve value rounding

* Resize preview via mouse dragging only when docked, not in when standalone window

* Improve black or white preview background handling, especially for standalone window

## 3.3.0

2022-04-25

### New

* **UI**: Color font support

## 3.2.2

2022-03-07

### Fix

* A case where the preview did not show

## 3.2.1

2022-03-03

### New

* Update sliders when font axes are added or removed

    When changing the *axes location of a master*, the sliders don’t update yet, as this is more tricky to implement. For now, just disable and enable the plugin for that to take effect.

## 3.2.0

2022-03-03

### New

* Hovering over the instances in the menu applies the instance preview right away

## 3.1.0

2022-03-03

### New

* **UI**: Master Mapping Window with editable matrix

* **UI**: Sliders remember their positions now when switching fonts

* **UI**: Radar Chart for Master Mapping

### Changes

* Don’t move window by dragging anywhere in the view

### Fix

* Standalone window only persist over any other app, when the setting for that is active

    This wasn’t properly working before. The user had to check and uncheck the setting before it did what it claimed to do.

* Prevent window flashing when switching font documents

    Very convenient when having the standalone window large on a second monitor

* **UI**: Draw only in foremost font

* **UI**: Deal with multiple open fonts now

* **UI**: Avoid preview padding to shrink below minimum size

## 3.0.10

2022-01-31

* Small changes under the hood

## 3.0.8

2021-10-29

### Fix

* Semi- use corner components

## 3.0.7

2021-10-29

### Changes

* Attempt to fix the hidden sliders when window is open

* Slightly more clear remove views method

* Clean up

## 3.0.6

2021-10-20

### Changes

* New: Web Chart for Involved Masters

## 3.0.5

2021-09-23

### Changes

* New: Option to hide current layer foreground

## 3.0.4

2021-09-23

### Changes

* Make slider binary if range is only 1 or <=10 (e.g. for italic axis)

    Public [#7](https://github.com/Mark2Mark/variable-font-preview/issues/7) 

* ) new: "Always On Top" If active it shows the window on top of other windows even if GlyphsApp is in the background

* Rename

* Add test font

## 3.0.3

2021-09-06

### Changes

* Remove debug logs

## 3.0.2

2021-06-16

* Small changes under the hood

## 3.0.1

2021-04-13

### Changes

* Add menu item "Open Registration Window"

* WIP re-introduce RTL

* Add purchase button

* Add new Icon to bundle

* Remove old Icon

## 3.0.0

2021-04-07

### Changes

* Also round drawn nodes and measurement if selected

* New: User choice to use rounded or decimal values with sliders

* Fix the missing instances by making sure to have only one instance of the context menu

* Only Draw if SpaceKey is not down:

* Slider tooltips suffice with integers

* Only measure if _showPreviewInGlyph

* Improve UI of selection measure

* Improve measurement, fix offset if "Center Preview Glyph"

* Min Height for Preview in EditTab

* Crosshair color

* Fix position for older OS

* Fix incredibly annoying tracking area issues

* Tiny UI changes to slider box

* Fix another newly introduced bug

* Fix a bug where the Magnifier came up when clicked into a spot where the attached view has been before

* Use shadow instead of border

* Improve Magnifier UI

### Fix

* #59 Update Menu Instances right after adding an instance

## 1.1.6

2021-01-28

* Small changes under the hood

## 1.1.5

2020-11-29

### Changes

* Number format for slider values: no thousand separator

## 1.1.4

2020-11-29

* Small changes under the hood

## 1.1.3

2020-07-22

### Changes

* New: Show Percentage Bars for Involved Masters

## 1.1.2

2020-07-02

* Small changes under the hood

## 1.1.1

2019-12-20

### Changes

* Undock Preview into Standalone Window

## 1.1.0

2019-12-19

* Small changes under the hood

