# CQCode.CQImage method

图片CQ码

```csharp
public static CQCode CQImage(string data, bool isFlash = false, bool useCache = true, 
    bool useProxy = true, int? timeout = null)
```

| parameter | description |
| --- | --- |
| data | 图片名/绝对路径/URL/base64 |
| isFlash | 是否为闪照，默认为`false` |
| useCache | 通过URL发送时有效,是否使用已缓存的文件 |
| useProxy | 通过URL发送时有效,是否通过代理下载文件 |
| timeout | 通过URL发送时有效,超时时间，默认为`null`(不超时) |

## See Also

* class [CQCode](../CQCode.md)
* namespace [Sora.Entities.CQCodes](../../Sora.md)

<!-- DO NOT EDIT: generated by xmldocmd for Sora.dll -->