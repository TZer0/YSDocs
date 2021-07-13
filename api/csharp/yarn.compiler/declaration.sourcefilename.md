# Declaration.SourceFileName Property

Gets the name of the file in which this Declaration was found.


```csharp
public string SourceFileName { get; }
```
## Remarks

If this [`Declaration`](/api/csharp/yarn.compiler/declaration.md) was not found in a Yarn
source file, this will be [`ExternalDeclaration`](/api/csharp/yarn.compiler/declaration.externaldeclaration.md).




## Namespace
[`Yarn.Compiler`](/api/csharp/yarn.compiler/README.md)

## Assembly
YarnSpinner.Compiler.dll

## Source
Defined in [YarnSpinner.Compiler/Compiler.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner.Compiler/Compiler.cs#L265), line 265.