---
title: EmfSetColorSpace
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_SETCOLORSPACE определяет текущий объект логического цветового пространства для графических операций.
type: docs
weight: 4320
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
## EmfSetColorSpace class

Запись EMR_SETCOLORSPACE определяет текущий объект логического цветового пространства для графических операций.

```csharp
public sealed class EmfSetColorSpace : EmfObjectManipulationRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfSetColorSpace](emfsetcolorspace)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfSetColorSpace`](../emfsetcolorspace). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/ihcs) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее индекс объекта логического цветового пространства в таблице объектов EMF (раздел 3.1. 1.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Примечания

Объект логического цветового пространства, определенный этой записью, ДОЛЖЕН использоваться в операциях рисования, которые определяется последующими записями EMF, до тех пор, пока другой объект логического цветового пространства не будет указан другой записью EMR_SETCOLORSPACE, или объект не будет удален записью EMR_DELETECOLORSPACE .

### Смотрите также

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->