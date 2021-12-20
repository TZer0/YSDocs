# FunctionType

Class in [Yarn](/api/csharp/yarn.md)

Inherits from `System.Object`

## Summary


A type that represents functions.


```csharp
public class FunctionType : IType
    {
    }
```

## Remarks


Functions have parameters and a return type, and can be called from
script. Instances of this type are created when the host
application registers new functions (such as through using the  <a href="yarn.library.registerfunction-7.md">RegisterFunction(string,Delegate)</a>  methods or similar.)


## Properties

|Name|Description|
|:---|:---|
|[Name](/api/csharp/yarn.functiontype.name.md)|Gets the name of this type.|
|[Description](/api/csharp/yarn.functiontype.description.md)|Gets a more verbose description of this type.|
|[Parent](/api/csharp/yarn.functiontype.parent.md)|Gets the parent of this type.|
|[ReturnType](/api/csharp/yarn.functiontype.returntype.md)|Gets the type of value that this function returns.|
|[Parameters](/api/csharp/yarn.functiontype.parameters.md)|Gets the list of the parameter types that this function is called with.|
|[Methods](/api/csharp/yarn.functiontype.methods.md)|Gets the collection of methods that are available on this type.|
