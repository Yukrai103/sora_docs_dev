# Sora assembly

## Sora.Entities namespace

| public type | description |
| --- | --- |
| class [Group](Sora.Entities/Group.md) | 群组实例 |
| class [Message](Sora.Entities/Message.md) | 消息实例 |
| class [OfflineFileInfo](Sora.Entities/OfflineFileInfo.md) | 离线文件信息 |
| class [User](Sora.Entities/User.md) | 用户类 |

## Sora.Entities.Base namespace

| public type | description |
| --- | --- |
| abstract class [BaseModel](Sora.Entities.Base/BaseModel.md) | 数据模型基类 |
| class [SoraApi](Sora.Entities.Base/SoraApi.md) | Sora API执行实例 |

## Sora.Entities.CQCodes namespace

| public type | description |
| --- | --- |
| class [CQCode](Sora.Entities.CQCodes/CQCode.md) | CQ码类 |

## Sora.Entities.CQCodes.CQCodeModel namespace

| public type | description |
| --- | --- |
| struct [At](Sora.Entities.CQCodes.CQCodeModel/At.md) | At某人 |
| struct [CardImage](Sora.Entities.CQCodes.CQCodeModel/CardImage.md) | 装逼大图 仅支持Go |
| struct [Code](Sora.Entities.CQCodes.CQCodeModel/Code.md) | Xml与Json集合 |
| struct [Face](Sora.Entities.CQCodes.CQCodeModel/Face.md) | QQ 表情 |
| struct [Forward](Sora.Entities.CQCodes.CQCodeModel/Forward.md) | 合并转发/合并转发节点 |
| struct [Gift](Sora.Entities.CQCodes.CQCodeModel/Gift.md) | 礼物 仅支持Go |
| struct [Image](Sora.Entities.CQCodes.CQCodeModel/Image.md) | 图片 |
| struct [Music](Sora.Entities.CQCodes.CQCodeModel/Music.md) | 音乐分享 仅发送 |
| struct [Node](Sora.Entities.CQCodes.CQCodeModel/Node.md) | 自定义合并转发节点 |
| class [NodeArray](Sora.Entities.CQCodes.CQCodeModel/NodeArray.md) | 转发消息的列表 |
| struct [Poke](Sora.Entities.CQCodes.CQCodeModel/Poke.md) | 群成员戳一戳 |
| struct [Record](Sora.Entities.CQCodes.CQCodeModel/Record.md) | 语音消息 |
| struct [Redbag](Sora.Entities.CQCodes.CQCodeModel/Redbag.md) | 接收红包 仅支持Go |
| struct [Reply](Sora.Entities.CQCodes.CQCodeModel/Reply.md) | 回复 |
| struct [Share](Sora.Entities.CQCodes.CQCodeModel/Share.md) | 链接分享 |
| struct [Text](Sora.Entities.CQCodes.CQCodeModel/Text.md) | 纯文本 |

## Sora.Entities.Info namespace

| public type | description |
| --- | --- |
| struct [FriendInfo](Sora.Entities.Info/FriendInfo.md) | 好友信息 |
| struct [GroupInfo](Sora.Entities.Info/GroupInfo.md) | 群信息 |
| struct [GroupMemberInfo](Sora.Entities.Info/GroupMemberInfo.md) | 群成员信息 |
| class [GroupRequestInfo](Sora.Entities.Info/GroupRequestInfo.md) | 群组请求信息 |
| struct [GroupSenderInfo](Sora.Entities.Info/GroupSenderInfo.md) | 群组消息发送者 |
| struct [PrivateSenderInfo](Sora.Entities.Info/PrivateSenderInfo.md) | 私聊消息发送者 |
| struct [UploadFileInfo](Sora.Entities.Info/UploadFileInfo.md) | 上传文件的信息 |
| struct [UserInfo](Sora.Entities.Info/UserInfo.md) | 用户信息 |

## Sora.Enumeration namespace

| public type | description |
| --- | --- |
| enum [CQFunction](Sora.Enumeration/CQFunction.md) | 消息段类型 |

## Sora.Enumeration.ApiEnum namespace

| public type | description |
| --- | --- |
| enum [APIStatusType](Sora.Enumeration.ApiEnum/APIStatusType.md) | API返回值 |
| enum [ClientType](Sora.Enumeration.ApiEnum/ClientType.md) | 客户端类型 |

## Sora.Enumeration.EventParamsType namespace

| public type | description |
| --- | --- |
| enum [AdminChangeType](Sora.Enumeration.EventParamsType/AdminChangeType.md) | 管理员变动类型 |
| enum [GroupRequestType](Sora.Enumeration.EventParamsType/GroupRequestType.md) | 群申请类型 |
| enum [HonorType](Sora.Enumeration.EventParamsType/HonorType.md) | 荣誉类型 |
| enum [MemberChangeType](Sora.Enumeration.EventParamsType/MemberChangeType.md) | 群成员变动类型 |
| enum [MemberRoleType](Sora.Enumeration.EventParamsType/MemberRoleType.md) | 成员权限等级 |
| enum [MessageType](Sora.Enumeration.EventParamsType/MessageType.md) | 消息类型 |
| enum [MusicShareType](Sora.Enumeration.EventParamsType/MusicShareType.md) | 音乐分享类型 |
| enum [MuteActionType](Sora.Enumeration.EventParamsType/MuteActionType.md) | 禁言操作类型 |
| enum [RequestType](Sora.Enumeration.EventParamsType/RequestType.md) | 请求类型 |

## Sora.EventArgs.SoraEvent namespace

| public type | description |
| --- | --- |
| class [AddGroupRequestEventArgs](Sora.EventArgs.SoraEvent/AddGroupRequestEventArgs.md) | 入群申请 |
| abstract class [BaseSoraEventArgs](Sora.EventArgs.SoraEvent/BaseSoraEventArgs.md) | 框架事件基类 |
| class [ConnectEventArgs](Sora.EventArgs.SoraEvent/ConnectEventArgs.md) | 客户端连接事件参数 |
| class [FileUploadEventArgs](Sora.EventArgs.SoraEvent/FileUploadEventArgs.md) | 群文件上传事件参数 |
| class [FriendAddEventArgs](Sora.EventArgs.SoraEvent/FriendAddEventArgs.md) | 好友添加事件参数 |
| class [FriendRecallEventArgs](Sora.EventArgs.SoraEvent/FriendRecallEventArgs.md) | 好友消息撤回事件 |
| class [FriendRequestEventArgs](Sora.EventArgs.SoraEvent/FriendRequestEventArgs.md) | 好友请求事件参数 |
| class [GroupAdminChangeEventArgs](Sora.EventArgs.SoraEvent/GroupAdminChangeEventArgs.md) | 管理员变动事件参数 |
| class [GroupCardUpdateEventArgs](Sora.EventArgs.SoraEvent/GroupCardUpdateEventArgs.md) | 成员名片变更事件参数 |
| class [GroupMemberChangeEventArgs](Sora.EventArgs.SoraEvent/GroupMemberChangeEventArgs.md) | 群成员数量变更事件参数 |
| class [GroupMessageEventArgs](Sora.EventArgs.SoraEvent/GroupMessageEventArgs.md) | 群消息事件参数 |
| class [GroupMuteEventArgs](Sora.EventArgs.SoraEvent/GroupMuteEventArgs.md) | 群禁言事件参数 |
| class [GroupPokeEventArgs](Sora.EventArgs.SoraEvent/GroupPokeEventArgs.md) | 群戳一戳事件参数 |
| class [GroupRecallEventArgs](Sora.EventArgs.SoraEvent/GroupRecallEventArgs.md) | 群消息撤回事件参数 |
| class [HonorEventArgs](Sora.EventArgs.SoraEvent/HonorEventArgs.md) | 授予荣誉事件参数 |
| class [LuckyKingEventArgs](Sora.EventArgs.SoraEvent/LuckyKingEventArgs.md) | 红包运气王事件参数 |
| class [OfflineFileEventArgs](Sora.EventArgs.SoraEvent/OfflineFileEventArgs.md) | 接收到离线文件事件参数 |
| class [PrivateMessageEventArgs](Sora.EventArgs.SoraEvent/PrivateMessageEventArgs.md) | 私聊消息事件参数 |

## Sora.EventArgs.WSSeverEvent namespace

| public type | description |
| --- | --- |
| abstract class [BaseServerEventArgs](Sora.EventArgs.WSSeverEvent/BaseServerEventArgs.md) | 服务器事件基类 |
| class [ConnectionEventArgs](Sora.EventArgs.WSSeverEvent/ConnectionEventArgs.md) | 服务器连接事件 |
| class [PongEventArgs](Sora.EventArgs.WSSeverEvent/PongEventArgs.md) | 服务器心跳包事件 |

## Sora.Server namespace

| public type | description |
| --- | --- |
| class [ServerConfig](Sora.Server/ServerConfig.md) | 服务器配置类 |
| class [SoraWSServer](Sora.Server/SoraWSServer.md) | Sora服务器实例 |

## Sora.Server.ServerInterface namespace

| public type | description |
| --- | --- |
| class [EventInterface](Sora.Server.ServerInterface/EventInterface.md) | Onebot事件接口 判断和分发基类事件 |

## Sora.Tool namespace

| public type | description |
| --- | --- |
| static class [ConsoleLog](Sora.Tool/ConsoleLog.md) | 控制台格式化Log类 |
| static class [Utils](Sora.Tool/Utils.md) | 工具类 |

<!-- DO NOT EDIT: generated by xmldocmd for Sora.dll -->