---
title: EmfPlusDrawDriverString
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusDrawDriverString определяет вывод текста с позициями символов.
type: docs
weight: 5940
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

Запись EmfPlusDrawDriverString определяет вывод текста с позициями символов.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring)(EmfPlusRecord) | Инициализирует новый экземпляр класса[`EmfPlusDrawDriverString`](../emfplusdrawdriverstring). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid) { get; set; } | Получает или задает идентификатор кисти 32-разрядное целое число без знака, указывающее либо цвет переднего плана текста, либо графическую кисть, в зависимости от значения флага S в Flags |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное число байтов данных в поле RecordData, которое следует. Это число не включает 12-байтовый заголовок записи. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags) { get; set; } | Получает или устанавливает флаги параметров строки драйвера 32-разрядное целое число без знака, указывающее интервал, ориентацию и качество рендеринга строки. . |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция , и о структуре запись. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount) { get; set; } | Получает или задает количество глифов 32-битное целое число без знака, указывающее количество глифов в строке |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos) { get; set; } | Получает или задает массив позиций глифа Массив объектов EmfPlusPointF (раздел 2.2.2.36), которые определяют выходную позицию глифа каждого символа. ДОЛЖНЫ быть элементы GlyphCount, которые имеют однозначное соответствие с элементами в массиве Glyphs. Позиции глифа вычисляются из позиции первого глифа, если установлен флаг DriverStringOptionsRealizedAdvance в флагах DriverStringOptions. В этом случае GlyphPos указывает положение только первого глифа. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs) { get; set; } | Получает или задает массив глифов Массив 16-битных значений, определяющих отображаемую текстовую строку. Если флаг DriverStringOptionsCmapLookup в поле DriverStringOptionsFlags установлен, каждое значение в этом массиве указывает символ Юникода. В противном случае каждое значение указывает индекс символьного глифа в объекте EmfPlusFont, заданном значением ObjectId в поле Flags. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor) { get; set; } | Получает или задает значение, указывающее, является ли данный экземпляр цветным. Этот бит указывает тип данных в поле BrushId. Если установлено, BrushId определяет значение цвета в объекте EmfPlusARGB (раздел 2.2.2.1). Если флажок не установлен, BrushId содержит индекс EMF+ Object Table объекта EmfPlusBrush (раздел 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent) { get; set; } | Получает или задает флаг наличия матрицы 32-разрядное целое число без знака, указывающее, присутствует ли матрица преобразования в поле TransformMatrix 0 - матрицы нет. 1 - матрица преобразования находится в поле TransformMatrix |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid) { get; set; } | Получает или задает идентификатор объекта. Индекс таблицы объектов EMF+ объекта &lt;see href="EmfPlusFont" /&gt; (раздел 2.2.1.3) для отображения текста. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее число байтов, выровненных по 32-разрядному выравниванию во всей записи, включая 12 -байтовый заголовок записи и данные, относящиеся к записи. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix) { get; set; } | Получает или задает матрицу преобразования Необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий преобразование, применяемое к каждое значение в текстовом массиве. Наличие этих данных определяется из поля MatrixPresent. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
