---
title: PointData
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает данные точки Массив точек Count указывающих конечные точки линий определяющих сплайн. В замкнутом кардинальном сплайне кривая продолжается через последнюю точку в массиве PointData и соединяется с первой точкой в массиве. Тип данных в этом массиве определяется полем Флаги следующим образомТип данных Значение Объект EmfPlusPointR раздел 2.2.2.37 Если флаг P установлен в Flags точки указывают относительное расположение. Объект EmfPlusPointF раздел 2.2.2.36 Если биты P и C установлены в поле Flags точки указывают абсолютные местоположения. Объект EmfPlusPoint раздел 2.2.2.35 Если бит P сброшен а бит C установлен в поле Flags точки указывают относительное расположение.
type: docs
weight: 40
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/
---
## EmfPlusDrawClosedCurve.PointData property

Получает или задает данные точки Массив точек Count, указывающих конечные точки линий, определяющих сплайн. В замкнутом кардинальном сплайне кривая продолжается через последнюю точку в массиве PointData и соединяется с первой точкой в массиве. Тип данных в этом массиве определяется полем Флаги следующим образом:Тип данных Значение Объект EmfPlusPointR (раздел 2.2.2.37) Если флаг P установлен в Flags, точки указывают относительное расположение. Объект EmfPlusPointF (раздел 2.2.2.36) Если биты P и C установлены в поле Flags, точки указывают абсолютные местоположения. Объект EmfPlusPoint (раздел 2.2.2.35) Если бит P сброшен, а бит C установлен в поле Flags, точки указывают относительное расположение.

```csharp
public PointF[] PointData { get; set; }
```

### Смотрите также

* struct [PointF](../../../aspose.imaging/pointf)
* class [EmfPlusDrawClosedCurve](../../emfplusdrawclosedcurve)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawclosedcurve)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
