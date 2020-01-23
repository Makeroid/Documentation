# Side Menu Layout

| Category | Requires | Version |
|:--------:|:-------:|:--------:|
|Layout > Navigation|API 19, Android 4.4 - 4.4.4 KitKat|2|

:mag: {>>Non-visible component<<}

## Overview

A non-visible component that creates a side menu.   
Side menus are navigation menus that slide from the left of the screen via a swipe-right gesture.

## Events

### On Menu Item Click

[[Event('Side Menu Layout', 'On Menu Item Click', 'title')]]

| Params | []() |
|--------|------|
|title|Text|


Triggers when the user clicks on an item of the Navigation Menu

## Methods

### Add Item

[[Method('Side Menu Layout', 'Add Item', False, 'title', 'image', 'enabled', 'checked', 'group')]]

| Params | []() |
|--------|------|
|title|Text|
|image|Text|
|enabled|Boolean|
|checked|Boolean|
|group|Number|


Add an item to the Navigation Menu

### Remove Item

[[Method('Side Menu Layout', 'Remove Item', False, 'title')]]

| Params | []() |
|--------|------|
|title|Text|


Remove an item from the Navigation Menu

### Update Item

[[Method('Side Menu Layout', 'Update Item', False, 'title', 'newTitle', 'image', 'enabled', 'checked')]]

| Params | []() |
|--------|------|
|title|Text|
|new Title|Text|
|image|Text|
|enabled|Boolean|
|checked|Boolean|


Update an item of the Navigation Menu

## Properties

### Background Color

<span class="chip chip-number">Number</span> <span class="chip chip-number">Default: <i>&HFFFFFFFF</i></span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Set the background color of the Sidemenu Layout

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Background Color')]]

### Circle Header Picture

<span class="chip chip-boolean">Boolean</span> <span class="chip chip-boolean">Default: <i>False</i></span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets (or not) the header picture to use a circle shape

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Circle Header Picture')]]

### Disabled Color

<span class="chip chip-number">Number</span> <span class="chip chip-number">Default: <i>&HFF9E9E9E</i></span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets the color of the disabled elements of the SideMenu

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Disabled Color')]]

### Enabled Color

<span class="chip chip-number">Number</span> <span class="chip chip-number">Default: <i>&HFF000000</i></span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets the color of the enabled elements of the SideMenu

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Enabled Color')]]

### Header Background Image

<span class="chip chip-text">Text</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets the Header Background Picture

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Header Background Image')]]

### Header Picture

<span class="chip chip-text">Text</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets the Header Picture of the Side Menu

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Header Picture')]]

### Header Subtitle

<span class="chip chip-text">Text</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets the Header Subtitle

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Header Subtitle')]]

### Header Title

<span class="chip chip-text">Text</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets the Header Title

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Header Title')]]

### Selected Color

<span class="chip chip-number">Number</span> <span class="chip chip-number">Default: <i>&HFFE81E63</i></span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="chip chip-rw">Read</span> <span class="chip chip-rw">Write</span> - <span class="chip chip-bd">Designer</span> <span class="chip chip-bd">Blocks</span> 

Sets the color of the selected element of the SideMenu

[[PropertyBlockGetterAndSetter('Side Menu Layout', 'Selected Color')]]