## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: badge, @tag: component-partial }}
{{#with badge.variations.default}}
    {{> badge content=this.content settings=this.settings}}
{{/with}}
{{! @INSERT :: END }}
