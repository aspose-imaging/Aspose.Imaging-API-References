---
title: EmfRectangle
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_RECTANGLE рисует прямоугольник. Прямоугольник обводится текущим Pen и заполняется текущей кистью.
type: docs
weight: 4160
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
## EmfRectangle class

Запись EMR_RECTANGLE рисует прямоугольник. Прямоугольник обводится текущим Pen и заполняется текущей кистью.

```csharp
public sealed class EmfRectangle : EmfDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfRectangle](emfrectangle#constructor)() | Инициализирует новый экземпляр[`EmfRectangle`](../emfrectangle) класс. |
| [EmfRectangle](emfrectangle#constructor_1)(EmfRecord) | Инициализирует новый экземпляр[`EmfRectangle`](../emfrectangle) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Box](../../aspose.imaging.fileformats.emf.emf.records/emfrectangle/box) { get; set; } | Получает или задает 128-битный объект WMF RectL, указанный в разделе 2.2.2.19 [MS-WMF], который указывает прямоугольник для рисования включительно-включающий. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Примечания

Текущая позиция не используется и не обновляется Rectangle. Если используется перо PS_NULL, размеры прямоугольника уменьшаются на 1 пиксель по высоте и на 1 пиксель меньше по ширине.

### Смотрите также

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
