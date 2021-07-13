# MarkupValue Struct

A value associated with a [`MarkupProperty`](/api/csharp/yarn.markup/markupproperty.md).


```csharp
public struct MarkupValue
```
## Remarks

You do not create instances of this struct yourself. It is created
by objects that can parse markup, such as [`Dialogue`](/api/csharp/yarn/dialogue.md).




## Properties
|Name|Description|
|:---|:---|
|[`BoolValue`](/api/csharp/yarn.markup/markupvalue.boolvalue.md)|Gets the bool value of this property.|
|[`FloatValue`](/api/csharp/yarn.markup/markupvalue.floatvalue.md)|Gets the float value of this property.|
|[`IntegerValue`](/api/csharp/yarn.markup/markupvalue.integervalue.md)|Gets the integer value of this property.|
|[`StringValue`](/api/csharp/yarn.markup/markupvalue.stringvalue.md)|Gets the string value of this property.|
|[`Type`](/api/csharp/yarn.markup/markupvalue.type.md)| Gets the value's type. |
## Methods
|Name|Description|
|:---|:---|
|[`ToString()`](/api/csharp/yarn.markup/markupvalue.tostring.md)||
## See Also
* [`ParseMarkup(String)`](/api/csharp/yarn/dialogue.parsemarkup-system.string-.md): 
Parses a line of text, and produces a [`MarkupParseResult`](/api/csharp/yarn.markup/markupparseresult.md) containing the results.

## Namespace
[`Yarn.Markup`](/api/csharp/yarn.markup/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs#L418), line 418.