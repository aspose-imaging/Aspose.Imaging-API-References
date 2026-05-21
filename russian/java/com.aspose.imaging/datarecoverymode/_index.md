---
title: "DataRecoveryMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Режим восстановления данных."
type: docs
weight: 38
url: /ru/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

Режим восстановления данных.
## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Восстановление данных не предполагается. |
| [ConsistentRecover](#ConsistentRecover) | Последовательный режим восстановления пытается восстановить все данные, пока повреждение не нарушает формат файла, и позволяет корректную дальнейшую обработку. |
| [MaximalRecover](#MaximalRecover) | Максимальный режим восстановления восстанавливает все данные, даже если структура формата файла повреждена, и дальнейшая обработка может привести к непредвиденным эффектам. |
### None {#None}
```
public static final int None
```


Восстановление данных не предполагается. Всякий раз, когда формат файла содержит повреждённые данные, выбрасывается соответствующее исключение.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


Последовательный режим восстановления пытается восстановить все данные, пока повреждение не нарушает формат файла, и позволяет корректную дальнейшую обработку.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


Максимальный режим восстановления восстанавливает все данные, даже если структура формата файла повреждена, и дальнейшая обработка может привести к непредвиденным эффектам.

