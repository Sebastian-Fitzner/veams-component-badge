# Badge

This blueprint is based on the blueprint of Veams-Components.

## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: badge, @tag: component
{{#with badge-bp}}
	{{#each data}}
		{{> c-badge this}}
	{{/each}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @id: scss-import, @tag: component
@import "components/_c-badge";
// @INSERT :: END
```
