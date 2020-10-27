# SoraApi.GetGroupMemberInfo method

获取群成员信息

```csharp
public ValueTask<ValueTuple<APIStatusType, GroupMemberInfo>> GetGroupMemberInfo(long groupId, 
    long userId, bool useCache = true)
```

| parameter | description |
| --- | --- |
| groupId | 群号 |
| userId | 用户ID |
| useCache | 是否使用缓存 |

## Return Value

[`APIStatusType`](../../Sora.Enumeration.ApiEnum/APIStatusType.md) API执行状态

[`GroupMemberInfo`](../../Sora.Entities.Info/GroupMemberInfo.md) 群成员信息

## See Also

* enum [APIStatusType](../../Sora.Enumeration.ApiEnum/APIStatusType.md)
* struct [GroupMemberInfo](../../Sora.Entities.Info/GroupMemberInfo.md)
* class [SoraApi](../SoraApi.md)
* namespace [Sora.Entities.Base](../../Sora.md)

<!-- DO NOT EDIT: generated by xmldocmd for Sora.dll -->