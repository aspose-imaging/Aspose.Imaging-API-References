---
title: EmfPolyPolygon16
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_POLYPOLYPOLYGON16 определяет серию замкнутых многоугольников. Каждый многоугольник обводится текущим пером и заполняется текущей кистью и режимом заливки полигона. Полигоны нарисованные этой записью могут перекрываться.
type: docs
weight: 4030
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/
---
## EmfPolyPolygon16 class

Запись EMR_POLYPOLYPOLYGON16 определяет серию замкнутых многоугольников. Каждый многоугольник обводится текущим пером и заполняется текущей кистью и режимом заливки полигона. Полигоны, нарисованные этой записью, могут перекрываться.

```csharp
public sealed class EmfPolyPolygon16 : EmfDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPolyPolygon16](emfpolypolygon16#constructor)() | Инициализирует новый экземпляр класса[`EmfPolyPolygon16`](../emfpolypolygon16). |
| [EmfPolyPolygon16](emfpolypolygon16#constructor_1)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfPolyPolygon16`](../emfpolypolygon16). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/apoints) { get; set; } | Получает или задает массив длины счетчика объектов WMF PointS, указанный в [MS-WMF] раздел 2.2.2.16, который определяет массив точек. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/bounds) { get; set; } | Получает или задает 128-битный объект RectL WMF, указанный в разделе [MS-WMF] 2.2.2.19, который указывает ограничивающий прямоугольник , в единицах устройства. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Примечания

Каждый полигон ДОЛЖЕН быть обведен текущим пером и заполнен текущим кистью и режим заливки полигонов, которые определены в контексте устройства воспроизведения. Полигоны, определенные этой записью, могут перекрываться.

### Смотрите также

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->