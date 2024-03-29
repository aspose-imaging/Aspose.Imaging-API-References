---
title: EmfCreateColorSpace
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_CREATECOLORSPACE создает объект логического цветового пространства из цветового профиля с именем a  состоящим из символов ASCII.
type: docs
weight: 3470
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
## EmfCreateColorSpace class

Запись EMR_CREATECOLORSPACE создает объект логического цветового пространства из цветового профиля с именем a , состоящим из символов ASCII.

```csharp
public sealed class EmfCreateColorSpace : EmfObjectCreationRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfCreateColorSpace](emfcreatecolorspace)(EmfRecord) | Инициализирует новый экземпляр[`EmfCreateColorSpace`](../emfcreatecolorspace) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/ihcs) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее индекс объекта логического цветового пространства в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранен, чтобы этот объект можно было повторно использовать или изменить. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/lcs) { get; set; } | Получает или задает объект WMF LogColorSpace ([MS-WMF], раздел 2.2.2.11), который может указывать имя цветового профиля в символах ASCII. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Примечания

Объект логического цветового пространства, определенный этой записью, может быть выбран в контексте устройства воспроизведения с помощью записи EMR_SETCOLORSPACE (раздел 2.3.8.7), которая определяет логическое цветовое пространство для использования в последующих графических операциях.

### Смотрите также

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
