---
title: EmfCreateColorSpaceW
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_CREATECOLORSPACEW создает объект логического цветового пространства из цветового профиля с именем состоящим из символов Unicode.
type: docs
weight: 3480
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
## EmfCreateColorSpaceW class

Запись EMR_CREATECOLORSPACEW создает объект логического цветового пространства из цветового профиля с именем, состоящим из символов Unicode.

```csharp
public sealed class EmfCreateColorSpaceW : EmfObjectCreationRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfCreateColorSpaceW](emfcreatecolorspacew)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfCreateColorSpaceW`](../emfcreatecolorspacew). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/cbdata) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее размер поля данных в байтах. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/data) { get; set; } | Получает или задает необязательный массив байтов, определяющий данные цветового профиля. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/dwflags) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое предоставляет информацию о данных в этой записи. |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/ihcs) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее индекс объекта логического цветового пространства в таблице объектов EMF (раздел 3.1. 1.1). Этот индекс ДОЛЖЕН быть сохранен, чтобы этот объект можно было повторно использовать или модифицировать. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/lcs) { get; set; } | Получает или задает объект WMF LogColorSpaceW ([MS-WMF], раздел 2.2.2.12), который может указывать имя цветового профиля в Символы Unicode UTF16-LE |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Примечания

Объект логического цветового пространства, определенный этой записью, может быть выбран в контексте устройства воспроизведения записью EMR_SETCOLORSPACE (раздел 2.3.8.7), которая определяет логическое цветовое пространство для использования в последующих графических операциях.

### Смотрите также

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->