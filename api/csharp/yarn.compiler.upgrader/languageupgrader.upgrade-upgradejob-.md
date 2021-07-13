# LanguageUpgrader.Upgrade Method

Upgrades a Yarn script from one version of the language to
another, producing both the fully upgraded text as well as a
collection of replacements.


```csharp
public static UpgradeResult Upgrade(UpgradeJob upgradeJob)
```

## Parameters
|Parameter|Description|
|:---|:---|
|[`UpgradeJob`](/api/csharp/yarn.compiler.upgrader/upgradejob.md) upgradeJob|The upgrade job to perform.|
## Return Type
[`UpgradeResult`](/api/csharp/yarn.compiler.upgrader/upgraderesult.md): An [`UpgradeResult`](/api/csharp/yarn.compiler.upgrader/upgraderesult.md) object containing the
results of the upgrade operation.



## Namespace
[`Yarn.Compiler.Upgrader`](/api/csharp/yarn.compiler.upgrader/README.md)

## Assembly
YarnSpinner.Compiler.dll

## Source
Defined in [YarnSpinner.Compiler/Upgrader/LanguageUpgrader.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner.Compiler/Upgrader/LanguageUpgrader.cs#L213), line 213.