<p align="right">
<a href="https://badge.fury.io/js/@veams/component-badge"><img src="https://badge.fury.io/js/@veams/component-badge.svg" alt="npm version" height="18"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Article

## Description

A simple badge component with different states (e.g. error, success, notice,...) and flexible content.

----------- 

## Installation 

### Installation with Veams

``` bash
veams install component badge
```
``` bash
veams -i c badge
```

----------- 

## Fields

### `badge.hbs`

#### Settings

| Parameter | Type | Value | Description |
|:--- |:---:|:---: |:--- |
| settings.badgeContextClass | String | `default` | Just pass a string |
| settings.badgeClasses | String | | Modifier classes |

#### Content

| Parameter | Type | Description |
|:--- |:---:|:--- |
| content.badgeType | String | Define your badge type (i.e. alert, error, notice, success) |
| content.badgeContent | String | Badge content |


------------

## Sass Options

There are global variables which you can change: 

| Variable | Value | Description |
|:--- | :---: |:--- |
| $badge-color-alert: | #fff6bf !default | Background color of alert badge. |
| $badge-color-error: | #fbe3e4 !default | Background color of error badge. |
| $badge-color-notice: | #e5edf8 !default | Background color of notice badge. |
| $badge-color-success: | #e6efc2 !default | Background color of success badge. |
