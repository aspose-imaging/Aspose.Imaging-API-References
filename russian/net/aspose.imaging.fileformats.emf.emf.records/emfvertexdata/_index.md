---
title: EmfVertexData
second_title: Справочник по Aspose.Imaging for .NET API
description: Объекты определяющие вершины прямоугольников или треугольников и соответствующие им цвета.
type: docs
weight: 4650
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
## EmfVertexData class

Объекты, определяющие вершины прямоугольников или треугольников, и соответствующие им цвета.

```csharp
public sealed class EmfVertexData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfVertexData](emfvertexdata)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [VertexIndexes](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexindexes) { get; set; } | Получает или задает массив объектов nTri GradientRectangle (раздел 2.2.7) или GradientTriangle объектов (раздел 2.2.8), в зависимости от значения поля ulMode. Каждый объект указывает индексы в массиве объектов TriVertex в поле VertexObjects. |
| [VertexObjects](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexobjects) { get; set; } | Получает или задает массив объектов nVer TriVertex (раздел 2.2.26). Каждый объект определяет положение и цвет вершины прямоугольника или треугольника, в зависимости от значения поля ulMode. |
| [VertexPadding](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexpadding) { get; set; } | Получает или задает необязательный массив переменной длины из nTri, умноженный на четыре байта , который ДОЛЖЕН присутствовать, если значение поля ulMode указывает на объекты GradientRectangle (раздел 2.2.7). Если значение поля ulMode указывает на объекты GradientTriangle (раздел 2.2.8), VertexPadding отсутствует. Это поле ДОЛЖНО быть проигнорировано. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
