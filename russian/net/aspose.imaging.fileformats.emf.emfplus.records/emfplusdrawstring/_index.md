---
title: EmfPlusDrawString
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusDrawString определяет вывод текста с форматированием строки
type: docs
weight: 6020
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
## EmfPlusDrawString class

Запись EmfPlusDrawString определяет вывод текста с форматированием строки

```csharp
public sealed class EmfPlusDrawString : EmfPlusDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusDrawString](emfplusdrawstring)(EmfPlusRecord) | Инициализирует новый экземпляр класса[`EmfPlusDrawString`](../emfplusdrawstring). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/brushid) { get; set; } | Получает или задает идентификатор кисти 32-битное целое число без знака, указывающее кисть, содержимое которой определяется битом S в поле Flags. Это определение используется для окрашивания текста переднего плана; то есть только сами глифы. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное число байтов данных в поле RecordData, которое следует. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция , и о структуре запись. |
| [FormatId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/formatid) { get; set; } | Получает или задает идентификатор формата 32-разрядное целое число без знака, указывающее индекс необязательного объекта EmfPlusStringFormat. (раздел 2.2.1.9) в таблице объектов EMF+. Этот объект определяет информацию о расположении текста и манипуляции с отображением для применения к строке |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/iscolor) { get; set; } | Получает или задает значение, указывающее, является ли данный экземпляр цветным. Если установлено, BrushId определяет цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если флажок не установлен, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+. |
| [LayoutRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/layoutrect) { get; set; } | Получает или задает прямоугольник макета Объект EmfPlusRectF (раздел 2.2.2.39), определяющий ограничивающую область пункт назначения, который получит строку |
| [Length](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/length) { get; set; } | Получает или задает длину 32-разрядное целое число без знака, указывающее количество символов в строке. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/objectid) { get; set; } | Получает или задает идентификатор объекта. Индекс объекта EmfPlusFont (раздел 2.2.1.3) в таблице объектов EMF+ для отображения текста. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее число байтов, выровненных по 32-разрядному выравниванию во всей записи, включая 12 -байтовый заголовок записи и данные, относящиеся к записи. |
| [StringData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/stringdata) { get; set; } | Получает или задает строковые данные Массив 16-битных символов Юникода, определяющий отображаемую строку |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
