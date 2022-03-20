# DialogueViewBase.OnLineStatusChanged(LocalizedLine)

Method in [DialogueViewBase](/api/csharp/yarn.unity.dialogueviewbase.md)

## Summary


Called by the DialogueRunner to indicate that the line that
this view is delivering has changed state.


```csharp
public virtual void OnLineStatusChanged(LocalizedLine dialogueLine)
```

## Remarks


Subclasses of  <a href="yarn.unity.dialogueviewbase.md">DialogueViewBase</a>  should override
this method to be notified when a line has become interrupted,
and when the line has finished being delivered by all views.

The default implementation does nothing.


## Parameters

|Name|Description|
|:---|:---|
|[Yarn.Unity.LocalizedLine](/api/csharp/yarn.unity.localizedline.md) dialogueLine|The  <a href="yarn.unity.localizedline.md">LocalizedLine</a>  that has changed state.|

## See Also

* [LineStatus](/api/csharp/yarn.unity.linestatus.md): The presentation status of a  <a href="yarn.unity.localizedline.md">LocalizedLine</a> .
