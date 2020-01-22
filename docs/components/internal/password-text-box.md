# Password Text Box

| Category | Version | Requires |
|:--------:|:-------:|:--------:|
|internal|6|API 19 - Android 4.4 - 4.4.4 KitKat|

## Overview

_<p>A box for entering passwords.  This is the same as the ordinary <code>TextBox</code> component except this does not display the characters typed by the user.</p><p>The value of the text in the box can be found or set through the <code>Text</code> property. If blank, the <code>Hint</code> property, which appears as faint text in the box, can provide the user with guidance as to what to type.</p> <p>Text boxes are usually used with the <code>Button</code> component, with the user clicking on the button when text entry is complete.</p>_

## Properties

### Background Color

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Background Color')]]

| Type | Default |
|:----:|:-------:|
|number|&H00000000|

The background color of the input box.  You can choose a color by name in the Designer or in the Blocks Editor.  The default background color is 'default' (shaded 3-D look).

### Cursor Color

<small>Available as Advanced Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Cursor Color')]]

| Type | Default |
|:----:|:-------:|
|number|&HFF000000|

The color of the cursor.

### Cursor Visible

<small>Available as Advanced Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Cursor Visible')]]

| Type | Default |
|:----:|:-------:|
|boolean|True|

Makes the cursor visible (the default) or invisible.

### Enabled

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Enabled')]]

| Type | Default |
|:----:|:-------:|
|boolean|True|

Whether the user can enter text into this input box.  By default, this is true.

### Font Bold

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Font Bold')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Whether the font for the text should be bold.  By default, it is not.

### Font Italic

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Font Italic')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Whether the text should appear in italics.  By default, it does not.

### Font Size

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Font Size')]]

| Type | Default |
|:----:|:-------:|
|number|14.0|

The font size for the text.  By default, it is 14.0 points.

### Font Typeface

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Font Typeface')]]

| Type | Default |
|:----:|:-------:|
|number|0|

The font for the text.  The value can be changed in the Designer.

### Font Typeface Import

<small>Available as Advanced Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Font Typeface Import')]]

| Type |
|:----:|
|text|

Set a custom font.

### Hint

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Hint')]]

| Type |
|:----:|
|text|

Text that should appear faintly in the input box to provide a hint as to what the user should enter.  This can only be seen if the <code>Text</code> property is empty.

### Hint Color

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Hint Color')]]

| Type | Default |
|:----:|:-------:|
|number|&HFF000000|

Set a custom hint text color.

### Rotation Angle

<small>Available as Advanced Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Rotation Angle')]]

| Type | Default |
|:----:|:-------:|
|number|0.0|

Sets the degrees that the textbox is rotated around the pivot point. Increasing values result in clockwise rotation.

### Text

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Text')]]

| Type |
|:----:|
|text|

Returns the textbox contents.

### Text Alignment

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Text Alignment')]]

| Type | Default |
|:----:|:-------:|
|number|0|

Whether the text should be left justified, centered, or right justified.  By default, text is left justified.

### Text Color

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Text Color')]]

| Type | Default |
|:----:|:-------:|
|number|&HFF000000|

The color for the text.  You can choose a color by name in the Designer or in the Blocks Editor.  The default text color is black.

### Visible

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Visible')]]

| Type | Default |
|:----:|:-------:|
|boolean|True|

Returns true iff the component is visible.

### Column



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Column')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Column property getter method.

### Current Position



:eyes: Read-Only property
[[PropertyBlockGetter('Password Text Box', 'Current Position')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Get the current cursor position.

### Enable Copy & Paste

:warning: **Deprecated** 

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Enable Copy & Paste')]]

| Type | Default |
|:----:|:-------:|
|boolean|None|

DEPRECATED since this feature is not working. Use 'Enabled' instead.

### Height



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Height')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's vertical height, measured in pixels.

### Height Percent



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Height Percent')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's vertical height as a percentage
 of the height of its parent Component.

### Line Color

:warning: **Deprecated** 

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Line Color')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Please delete this block from your project.This block is deprecated and not longer supported.

### Row



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Row')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Row property getter method.

### Text Length



:eyes: Read-Only property
[[PropertyBlockGetter('Password Text Box', 'Text Length')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Returns the current text length as number.

### Width



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Width')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's horizontal width, measured in pixels.

### Width Percent



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Password Text Box', 'Width Percent')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's horizontal width as a percentage
 of the Width of its parent Component.