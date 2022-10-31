---
title: DataRecoveryMode
second_title: Aspose.Imaging for Java API Reference
description: The data recovery mode.
type: docs
weight: 38
url: /java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

The data recovery mode.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No data recovery is implied. |
| [ConsistentRecover](#ConsistentRecover) | The consistent recovery mode tries to recover all data as long as corruption does not break the file format and allows correct further processing. |
| [MaximalRecover](#MaximalRecover) | The maximal recovery mode recovers all data even if the file format has corrupted structure and further processing may yield unattended effects. |
### None {#None}
```
public static final int None
```


No data recovery is implied. Whenever the file format has some corrupted data the appropriate exception is thrown.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


The consistent recovery mode tries to recover all data as long as corruption does not break the file format and allows correct further processing.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


The maximal recovery mode recovers all data even if the file format has corrupted structure and further processing may yield unattended effects.

