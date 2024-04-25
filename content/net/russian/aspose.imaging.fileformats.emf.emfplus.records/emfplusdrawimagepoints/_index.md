---
title: EmfPlusDrawImagePoints
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusDrawImagePoints определяет рисование масштабированного изображения внутри параллелограмма.
type: docs
weight: 5970
url: /ru/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

Запись EmfPlusDrawImagePoints определяет рисование масштабированного изображения внутри параллелограмма.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect) { get; set; } | Получает или задает значение, указывающее, [применяется ли эффект]. Этот бит указывает, что рендеринг изображения включает применение эффекта. 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed) { get; set; } | Получает или задает значение, указывающее, сжаты ли данные PointData. Этот бит указывает, указывает ли поле PointData сжатые данные. Если установлено, PointData указывает абсолютные местоположения в координатном пространстве с 16-битными целочисленными координатами . Если флажок не установлен, PointData указывает абсолютные местоположения в координатном пространстве с 32-битными координатами с плавающей запятой. Примечание. Если установлен флаг P (ниже), этот флаг не определен и ДОЛЖЕН игнорироваться. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid) { get; set; } | Получает или задает 32-разрядное целое число без знака, содержащее индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid) { get; set; } | Получает или задает идентификатор объекта. Индекс объекта EmfPlusImage (раздел 2.2.1.4) в таблице объектов EMF+ , указывающий изображение для визуализации. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata) { get; set; } | Получает или задает массив точек Count, определяющих три точки параллелограмма. Три точки представляют верхний левый, верхний правый и нижний левый углы параллелограмма . Четвертая точка параллелограмма экстраполируется из первых трех. К части изображения, заданной полем SrcRect, СЛЕДУЕТ применять масштабирование и преобразование shearing , если это необходимо, чтобы поместиться внутри параллелограмма. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative) { get; set; } | Получает или задает значение, указывающее, является ли это[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints)является относительным. Этот бит указывает, указывает ли поле PointData относительное или абсолютное местоположение. В случае первого элемента the в PointData предполагается предыдущее местоположение с координатами (0,0). Если флажок не установлен, PointData указывает абсолютные местоположения в соответствии с флагом C. Примечание. Если этот флаг установлен, флаг C (выше) не определен и ДОЛЖЕН игнорироваться. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect) { get; set; } | Получает или задает объект EmfPlusRectF (раздел 2.2.2.39), который определяет часть изображения для визуализации. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit) { get; set; } | Получает или задает 32-разрядное целое число со знаком, определяющее единицы измерения поля SrcRect. Это ДОЛЖНО быть значением UnitPixel перечисления UnitType (раздел 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Примечания

EmfPlusImage может указывать растровое изображение или метафайл. Цветами изображения можно управлять во время рендеринга. Их можно исправить, затемнить, осветлить и удалить.

### Смотрите также

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
