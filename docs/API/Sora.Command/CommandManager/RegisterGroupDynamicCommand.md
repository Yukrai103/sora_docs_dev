# CommandManager.RegisterGroupDynamicCommand method

动态注册指令

```csharp
public Guid RegisterGroupDynamicCommand(string[] cmdExps, 
    Func<GroupMessageEventArgs, ValueTask> groupCommand, MatchType matchType = MatchType.Full, 
    RegexOptions regexOptions = RegexOptions.None, Action<Exception> exceptionHandler = null, 
    MemberRoleType memberRole = MemberRoleType.Member, bool suCommand = false, int priority = 0, 
    long[] sourceGroups = null, long[] sourceUsers = null, string desc = "")
```

| parameter | description |
| --- | --- |
| cmdExps | 指令表达式 |
| groupCommand | 指令执行定义 |
| matchType | 匹配类型 |
| regexOptions | 正则选项 |
| exceptionHandler | 异常处理 |
| memberRole | 成员权限限制 |
| suCommand | 机器人管理员限制 |
| priority | 优先级 |
| sourceGroups | 群组限制 |
| sourceUsers | 成员限制 |
| desc | 描述 |

## See Also

* class [GroupMessageEventArgs](../../Sora.EventArgs.SoraEvent/GroupMessageEventArgs.md)
* enum [MatchType](../../Sora.Enumeration/MatchType.md)
* enum [MemberRoleType](../../Sora.Enumeration.EventParamsType/MemberRoleType.md)
* class [CommandManager](../CommandManager.md)
* namespace [Sora.Command](../../Sora.md)

<!-- DO NOT EDIT: generated by xmldocmd for Sora.dll -->