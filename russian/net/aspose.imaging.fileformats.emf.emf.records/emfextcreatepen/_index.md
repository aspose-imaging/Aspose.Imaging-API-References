---
title: EmfExtCreatePen
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_EXTCREATEPEN определяет расширенное логическое перо для графических операций. An можно указать необязательный DIB для использования в качестве стиля линии.
type: docs
weight: 3630
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
## EmfExtCreatePen class

Запись EMR_EXTCREATEPEN определяет расширенное логическое перо для графических операций. An можно указать необязательный DIB для использования в качестве стиля линии.

```csharp
public sealed class EmfExtCreatePen : EmfObjectCreationRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfExtCreatePen](emfextcreatepen#constructor)() | Инициализирует новый экземпляр[`EmfExtCreatePen`](../emfextcreatepen) класс. |
| [EmfExtCreatePen](emfextcreatepen#constructor_1)(EmfRecord) | Инициализирует новый экземпляр[`EmfExtCreatePen`](../emfextcreatepen) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/bitmapbuffer) { get; set; } | Получает или задает необязательный буфер, содержащий упакованный DIB в форме WMF DeviceIndependentBitmap object ([MS-WMF], раздел 2.2.2.9). Не требуется, чтобы он был непрерывным с фиксированной частью EMR_EXTCREATEPEN record . |
| [Elp](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/elp) { get; set; } | Получает или задает объект LogPenEx (раздел 2.2.20), указывающий расширенное логическое перо с атрибутами, включая необязательный массив стилей линий. |
| [IhPen](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/ihpen) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее индекс расширенного логического объекта пера в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранен, чтобы этот объект можно было повторно использовать или изменить. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Смотрите также

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
