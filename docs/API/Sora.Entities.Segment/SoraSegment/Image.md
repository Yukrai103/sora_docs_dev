# SoraSegment.Image method

图片 消息段

```csharp
public static SoraSegment Image(string data, bool useCache = true, int? threadCount = null)
```

| parameter | description |
| --- | --- |
| data | 图片名/绝对路径/URL/base64 |
| useCache | 通过URL发送时有效,是否使用已缓存的文件 |
| threadCount | 通过URL发送时有效,通过网络下载图片时的线程数,默认单线程 |

## See Also

* struct [SoraSegment](../SoraSegment.md)
* namespace [Sora.Entities.Segment](../../Sora.md)

<!-- DO NOT EDIT: generated by xmldocmd for Sora.dll -->