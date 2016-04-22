# Font Object (JavaScript API for Word)

_Word 2016, Word for iPad, Word for Mac_

Represents a font.

## Properties

| Property	   | Type	|Description
|:---------------|:--------|:----------|
|bold|bool|Gets or sets a value that indicates whether the font is bold. True if the font is formatted as bold, otherwise, false.|
|color|string|Gets or sets the color for the specified font. You can provide the value in the '#RRGGBB' format or the color name.|
|doubleStrikeThrough|bool|Gets or sets a value that indicates whether the font has a double strike through. True if the font is formatted as double strikethrough text, otherwise, false.|
|highlightColor|string|Gets or sets the highlight color for the specified font. You can provide the value as either in the '#RRGGBB' format or the color name.|
|italic|bool|Gets or sets a value that indicates whether the font is italicized. True if the font is italicized, otherwise, false.|
|name|string|Gets or sets a value that represents the name of the font.|
|strikeThrough|bool|Gets or sets a value that indicates whether the font has a strike through. True if the font is formatted as strikethrough text, otherwise, false.|
|subscript|bool|Gets or sets a value that indicates whether the font is a subscript. True if the font is formatted as subscript, otherwise, false.|
|superscript|bool|Gets or sets a value that indicates whether the font is a superscript. True if the font is formatted as superscript, otherwise, false.|
|underline|string|Gets or sets a value that indicates the font's underline type. 'None' if the font is not underlined. Possible values are: `None` No underline.,`Single` A single underline. This is the default value.,`Word` Only underline individual words.,`Double` A double underline.,`Dotted` A dotted underline.,`Hidden` A hidden underline.,`Thick` A single thick underline.,`DashLine` A single dash underline.,`DotLine` A single dot underline.,`DotDashLine` An alternating dot-dash underline.,`TwoDotDashLine` An alternating dot-dot-dash underline.,`Wave` A single wavy underline.|

_See property access [examples.](#property-access-examples)_

## Relationships
| Relationship | Type	|Description|
|:---------------|:--------|:----------|
|size|[float](float.md)|Gets or sets a value that represents the font size in points.|

## Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[load(param: object)](#loadparam-object)|void|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|

## Method Details


### load(param: object)
Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.

#### Syntax
```js
object.load(param);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|
|param|object|Optional. Accepts parameter and relationship names as delimited string or an array. Or, provide [loadOption](loadoption.md) object.|

#### Returns
void