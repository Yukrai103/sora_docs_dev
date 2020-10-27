# EventInterface.EventAsyncCallBackHandler&lt;TEventArgs&gt; delegate

Onebot事件回调

```csharp
public delegate ValueTask EventAsyncCallBackHandler<in TEventArgs>(object sender, 
    TEventArgs eventArgs)
    where TEventArgs : EventArgs;
```

| parameter | description |
| --- | --- |
| TEventArgs | 事件参数 |
| sender | 产生事件的客户端 |
| eventArgs | 事件参数 |

## See Also

* class [EventInterface](EventInterface.md)
* namespace [Sora.Server.ServerInterface](../Sora.md)

<!-- DO NOT EDIT: generated by xmldocmd for Sora.dll -->