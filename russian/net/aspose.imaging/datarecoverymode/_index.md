---
title: DataRecoveryMode
second_title: Справочник по Aspose.Imaging for .NET API
description: Режим восстановления данных.
type: docs
weight: 800
url: /ru/net/aspose.imaging/datarecoverymode/
---
## DataRecoveryMode enumeration

Режим восстановления данных.

```csharp
public enum DataRecoveryMode
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| None | `0` | Восстановление данных не предполагается. Всякий раз, когда формат файла содержит поврежденные данные, выдается соответствующее исключение. |
| ConsistentRecover | `1` | Режим последовательного восстановления пытается восстановить все данные до тех пор, пока повреждение не нарушает формат файла и позволяет корректную дальнейшую обработку. |
| MaximalRecover | `2` | Максимальный режим восстановления восстанавливает все данные, даже если формат файла имеет поврежденную структуру, и дальнейшая обработка может привести к нежелательным последствиям. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->