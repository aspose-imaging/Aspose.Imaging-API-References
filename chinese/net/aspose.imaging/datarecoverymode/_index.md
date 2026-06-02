---
title: "枚举 DataRecoveryMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.DataRecoveryMode 枚举。数据恢复模式"
type: docs
weight: 810
url: /zh/net/aspose.imaging/datarecoverymode/
---
## DataRecoveryMode enumeration

数据恢复模式。

```csharp
public enum DataRecoveryMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 不暗示数据恢复。每当文件格式出现损坏数据时，将抛出相应的异常。 |
| ConsistentRecover | `1` | 一致恢复模式尝试在损坏未破坏文件格式的前提下恢复所有数据，并允许正确的后续处理。 |
| MaximalRecover | `2` | 最大恢复模式即使在文件格式结构损坏的情况下也会恢复所有数据，后续处理可能产生未预期的效果。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


