# AdMob Interstitial

| Category | Version | Requires |
|:--------:|:-------:|:--------:|
|Advertising|4|API 19 - Android 4.4 - 4.4.4 KitKat|

:mag: {>>Non-visible component<<}

## Overview

_An interstitial ad is a full-page ad. AdMobInterstitial component allows you to monetize your app. You must have a valid AdMob account and AdUnitId that can be obtained from http://www.google.com/AdMob . If your id is invalid, the AdMobInterstitial will not display on the emulator or the device. Warning: Make sure you're in test mode during development to avoid being disabled for clicking your own ads. _

## Properties

### Ad Enabled

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Ad Enabled')]]

| Type | Default |
|:----:|:-------:|
|boolean|True|

This property must be set to true to receive ads.

### Ad Unit ID

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Ad Unit ID')]]

| Type | Default |
|:----:|:-------:|
|text|ca-app-pub-3940256099942544/1033173712|

_No description available_

### Interstitial Commission

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Interstitial Commission')]]

| Type | Default |
|:----:|:-------:|
|text|unity|

Sets the ad network used to take the commission.

### Consent Development Mode

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Consent Development Mode')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

If enabled you will see the consent dialog no matter if you are located in Europe or not. Please use this option only in development.  If this setting is enabled ALL taken consents will not be saved.

### Consent Message

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Consent Message')]]

| Type | Default |
|:----:|:-------:|
|text|Can we continue to use your data to tailor ads for you?|

The message for the consent dialog.

### Consent Title

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Consent Title')]]

| Type | Default |
|:----:|:-------:|
|text|Data Protection|

The title for the consent dialog.

### Target Age

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Target Age')]]

| Type | Default |
|:----:|:-------:|
|number|0|

Leave 0 for targeting ALL ages

### Target For Children

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Target For Children')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

Indicate whether you want Google to treat your content as child-directed when you make an ad request. Info here: https://developers.google.com/mobile-ads-sdk/docs/admob/android/targeting#child-directed_setting

### Target Gender

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Target Gender')]]

| Type | Default |
|:----:|:-------:|
|text|ALL|

_No description available_

### Test Mode

<small>Available as Common Property</small>

:eyes::pencil: Read-Write property
[[PropertyBlockGetterAndSetter('AdMob Interstitial', 'Test Mode')]]

| Type | Default |
|:----:|:-------:|
|boolean|False|

If you want to test the component then that this property to true. Then you will receive test ads.

### Personalized Result



:eyes: Read-Only property
[[PropertyBlockGetter('AdMob Interstitial', 'Personalized Result')]]

| Type | Default |
|:----:|:-------:|
|boolean|None|

Returns the current personalized consent. If true user has consent to personalized ads.