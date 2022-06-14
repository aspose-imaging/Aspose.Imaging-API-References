---
title: Records
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или устанавливает записи.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.emf/metaimage/records/
---
## MetaImage.Records property

Получает или устанавливает записи.

```csharp
public virtual MetaObjectList Records { get; set; }
```

### Стоимость имущества

Записи.

### Примеры

В этом примере показано, как загрузить изображение WMF из файла и перечислить все его записи.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
     // Кэшировать данные для загрузки всех записей.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

     // Ключ — тип записи, значение — количество записей этого типа в образе WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

     // Собираем статистику 
    foreach (Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRecord obj in emfImage.Records)
    {
        System.Type objType = obj.GetType();
        if (!types.ContainsKey(objType))
        {
            types.Add(objType, 1);
        }
        else
        {
            types[objType]++;
        }
    }

     // Распечатать статистику
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

 // Вывод может выглядеть так: 
 //Общее количество записей: 1188
 //Тип записи Count
 //--------------------------------
// Заголовок EmfMetafile: 1
 //EmfSetBkMode: 1
 //EmfSetTextAlign: 1
 //EmfSetRop2: 1
 //EmfSetWorldTransform: 1
 //EmfExtSelectClipRgn: 1
 //EmfCreateBrushIndirect: 113
 //EmfSelectObject: 240
 //EmfCreatePen: 116
 //EmfSetPolyFillMode: 1
 //EmfBeginPath: 120
 //EmfMoveToEx: 122
 //EmfPolyBezierTo16: 36
 //EmfLineTo: 172
 //EmfCloseРисунок: 14
 //EmfEndPath: 120
 //EmfStrokeAndFillPath: 113
//EmfStrokePath: 7
 //EmfSetTextColor: 2
 //EmfExtCreateFontIndirectW: 2
 //EmfExtTextOutW: 2
 //EmfStretchBlt: 1
//ЭмфЭоф: 1
```

В этом примере показано, как загрузить изображение EMF из файла и перечислить все его записи.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
     // Кэшировать данные для загрузки всех записей.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

     // Ключ — тип записи, значение — количество записей этого типа в образе WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

     // Собираем статистику 
    foreach (Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRecord obj in emfImage.Records)
    {
        System.Type objType = obj.GetType();
        if (!types.ContainsKey(objType))
        {
            types.Add(objType, 1);
        }
        else
        {
            types[objType]++;
        }
    }

     // Распечатать статистику
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

 // Вывод может выглядеть так: 
 //Общее количество записей: 1188
 //Тип записи Count
 //--------------------------------
// Заголовок EmfMetafile: 1
 //EmfSetBkMode: 1
 //EmfSetTextAlign: 1
 //EmfSetRop2: 1
 //EmfSetWorldTransform: 1
 //EmfExtSelectClipRgn: 1
 //EmfCreateBrushIndirect: 113
 //EmfSelectObject: 240
 //EmfCreatePen: 116
 //EmfSetPolyFillMode: 1
 //EmfBeginPath: 120
 //EmfMoveToEx: 122
 //EmfPolyBezierTo16: 36
 //EmfLineTo: 172
 //EmfCloseРисунок: 14
 //EmfEndPath: 120
 //EmfStrokeAndFillPath: 113
//EmfStrokePath: 7
 //EmfSetTextColor: 2
 //EmfExtCreateFontIndirectW: 2
 //EmfExtTextOutW: 2
 //EmfStretchBlt: 1
//ЭмфЭоф: 1
```

### Смотрите также

* class [MetaObjectList](../../metaobjectlist)
* class [MetaImage](../../metaimage)
* пространство имен [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
