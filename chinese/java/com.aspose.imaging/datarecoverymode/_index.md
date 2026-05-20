---
title: "DataRecoveryMode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "数据恢复模式。"
type: docs
weight: 38
url: /zh/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

数据恢复模式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 不暗示数据恢复。 |
| [ConsistentRecover](#ConsistentRecover) | 一致恢复模式尝试在腐败未破坏文件格式的前提下恢复所有数据，并允许正确的后续处理。 |
| [MaximalRecover](#MaximalRecover) | 最大恢复模式即使在文件格式结构已损坏的情况下也会恢复所有数据，但后续处理可能产生未预期的效果。 |
### None {#None}
```
public static final int None
```


不暗示数据恢复。每当文件格式出现部分损坏数据时，将抛出相应的异常。

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


一致恢复模式尝试在腐败未破坏文件格式的前提下恢复所有数据，并允许正确的后续处理。

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


最大恢复模式即使在文件格式结构已损坏的情况下也会恢复所有数据，但后续处理可能产生未预期的效果。

