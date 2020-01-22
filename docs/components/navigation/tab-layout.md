# Tab Layout

| Category | Version | Requires |
|:--------:|:-------:|:--------:|
|Navigation|1|API 19 - Android 4.4 - 4.4.4 KitKat|

## Overview

_A visible component that groups other layout components such that only one of its children is shown at a time. Each of the child layouts can be accessed either by swiping left and right, or using the tabs at the top._

## Properties

### Tabs Active Text Color

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Tabs Active Text Color')]]

| Type | Default |
|:----:|:-------:|
|number|&HFFFF4081|

Specifies the tab's text color for active tab's.

### Tabs Background Color

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Tabs Background Color')]]

| Type | Default |
|:----:|:-------:|
|number|&HFF3F51B5|

Specifies the tab's background color.

### Tabs Indicator Color

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Tabs Indicator Color')]]

| Type | Default |
|:----:|:-------:|
|number|&HFFFFFFFF|

Specifies the tab's indicator color.

### Tabs Mode

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Tabs Mode')]]

| Type | Default |
|:----:|:-------:|
|number|1|

Choose the mode used for the tab's. If no mode is specified, 'Scrollable' is taken as 'Default'. Use '0' for scrollable and '1' for fixed.

### Tabs Text Color

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Tabs Text Color')]]

| Type | Default |
|:----:|:-------:|
|number|&HFFFFFFFF|

Specifies the tab's text color for not selected tab's.

### Visible

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Visible')]]

| Type | Default |
|:----:|:-------:|
|boolean|True|

Specifies whether the component should be visible on the screen. Value is true if the component is showing and false if hidden.

### Column



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Column')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Column property getter method.

### Get Current Tab



:eyes: Read-Only property
[[PropertyBlockGetter('Tab Layout', 'Get Current Tab')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Get the current selected tab.

### Row



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Row')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Row property getter method.

### Select Tab



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Select Tab')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Select a tab which is then the active tab.

### Width



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Width')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's horizontal width, measured in pixels.

### Width Percent



:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('Tab Layout', 'Width Percent')]]

| Type | Default |
|:----:|:-------:|
|number|None|

Specifies the component's horizontal width as a percentage
 of the Width of its parent Component.