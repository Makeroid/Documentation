# Surface View

| Category | Version | Requires |
|:--------:|:-------:|:--------:|
|Views|2|API 19 - Android 4.4 - 4.4.4 KitKat|

## Overview

_A visible component that shows a live preview of the user''s camera as its background._

## Properties

### Align Horizontal

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Align Horizontal')]]

| Type | Default |
|:----:|:-------:|
|number|1|

A number that encodes how contents of the arrangement are aligned  horizontally. The choices are: 1 = left aligned, 2 = right aligned,  3 = horizontally centered.  Alignment has no effect if the arrangement's width is automatic.

### Align Vertical

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Align Vertical')]]

| Type | Default |
|:----:|:-------:|
|number|1|

_No description available_

### Clickable

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Clickable')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Set the surface view component clickable or not clickable.

### Detect Faces

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Detect Faces')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

If enabled you can detect how many faces are in the front of the camera.

### Save Preview As File

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Save Preview As File')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Enable this block to enable the "Got Preview" event to get a image file from the camera preview.

### Use Back Camera

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Use Back Camera')]]

| Type | Default |
|:----:|:-------:|
|boolean|True|

If enabled you will open the back camera for the camera preview, else you open the front camera. The block detect automatic if there is a device camera available or not.

### Visible

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Visible')]]

| Type | Default |
|:----:|:-------:|
|boolean|True|

Returns true iff the component is visible.

### Column



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Column')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Column property getter method.

### Flashlight



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Flashlight')]]

| Type | Default |
|:----:|:-------:|
|boolean|None|

Turn on or off the device flashlight. The function knows automatic if there is a flash/ torch available.

### Height



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Height')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's vertical height, measured in pixels.

### Height Percent



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Height Percent')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's vertical height as a percentage
 of the height of its parent Component.

### Row



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Row')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Row property getter method.

### Width



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Width')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's horizontal width, measured in pixels.

### Width Percent



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Surface View', 'Width Percent')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's horizontal width as a percentage
 of the Width of its parent Component.