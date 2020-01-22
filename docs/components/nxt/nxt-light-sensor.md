# NXT Light Sensor

| Category | Version | Requires |
|:--------:|:-------:|:--------:|
|nxt|1|API 19 - Android 4.4 - 4.4.4 KitKat|

:mag: {>>Non-visible component<<}

## Overview

_A component that provides a high-level interface to a light sensor on a LEGO MINDSTORMS NXT robot._

## Properties

### Above Range Event Enabled

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Above Range Event Enabled')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Whether the AboveRange event should fire when the light level goes above the TopOfRange.

### Below Range Event Enabled

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Below Range Event Enabled')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Whether the BelowRange event should fire when the light level goes below the BottomOfRange.

### Bluetooth Client

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Bluetooth Client')]]

| Type |
|:----:|
|component|

The BluetoothClient component that should be used for communication.

### Bottom Of Range

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Bottom Of Range')]]

| Type | Default |
|:----:|:-------:|
|number|256|

The bottom of the range used for the BelowRange, WithinRange, and AboveRange events.

### Generate Light

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Generate Light')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Whether the light sensor should generate light.

### Sensor Port

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Sensor Port')]]

| Type | Default |
|:----:|:-------:|
|text|3|

The sensor port that the sensor is connected to.

### Top Of Range

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Top Of Range')]]

| Type | Default |
|:----:|:-------:|
|number|767|

The top of the range used for the BelowRange, WithinRange, and AboveRange events.

### Within Range Event Enabled

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('NXT Light Sensor', 'Within Range Event Enabled')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Whether the WithinRange event should fire when the light level goes between the BottomOfRange and the TopOfRange.