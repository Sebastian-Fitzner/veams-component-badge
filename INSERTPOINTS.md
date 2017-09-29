## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: badge, @tag: component-partial }}
{{#with badge-bp.variations.default}}
    {{> c-badge content=this.content settings=this.settings}}
{{/with}}
{{! @INSERT :: END }}