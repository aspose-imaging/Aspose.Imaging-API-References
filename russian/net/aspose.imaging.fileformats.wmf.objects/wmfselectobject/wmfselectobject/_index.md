---
title: WmfSelectObject
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаWmfSelectObjectaspose.imaging.fileformats.wmf.objects/wmfselectobject.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.wmf.objects/wmfselectobject/wmfselectobject/
---
## WmfSelectObject(WmfGraphicObject) {#constructor_1}

Инициализирует новый экземпляр класса[`WmfSelectObject`](../../wmfselectobject).

```csharp
public WmfSelectObject(WmfGraphicObject wmfObject)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| wmfObject | WmfGraphicObject | Объект WMF. |

### Смотрите также

* class [WmfGraphicObject](../../wmfgraphicobject)
* class [WmfSelectObject](../../wmfselectobject)
* пространство имен [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfselectobject)
* сборка [Aspose.Imaging](../../../)

---

## WmfSelectObject() {#constructor}

Инициализирует новый экземпляр класса[`WmfSelectObject`](../../wmfselectobject).

```csharp
public WmfSelectObject()
```

### Примеры

В следующем примере показано, как установить цвет фона для WMF. На самом деле он рисует прямоугольник фонового цвета, прежде чем рисовать все остальные объекты.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image2.wmf";
string outputFilePath = dir + "ChangeBackground_" + "image2.wmf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleWmf((Aspose.Imaging.FileFormats.Wmf.WmfImage)image, Aspose.Imaging.Color.Blue);
    image.Save(outputFilePath);
}

/// <summary>
 /// Вспомогательный метод для изменения фона WMF. 
/// </summary>
public static void AddBackgroundRectangleWmf(Aspose.Imaging.FileFormats.Wmf.WmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

     //Установить Rectangle
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle rectangle = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle();
    rectangle.Rectangle = image.FrameBounds;

     //Установить кисть
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect brush = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

     //Выберите кисть
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject(brush);

     //Удалить кисть
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject(brush);

     //Добавить записи
    image.Records.Insert(0, brush);
    image.Records.Insert(1, selectObject);
    image.Records.Insert(2, rectangle);
    image.Records.Insert(3, deleteObject);
}
```

### Смотрите также

* class [WmfSelectObject](../../wmfselectobject)
* пространство имен [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfselectobject)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->