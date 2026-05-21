---
title: "EmfImage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة EmfImage. قم بتخزين البيانات مؤقتًا بكفاءة ومنع التحميل المتكرر من DataStreamContainer الأساسي باستخدام هذه الطريقة. عزّز الأداء وسهّل الوصول إلى البيانات في تطبيقك مع تحسين استهلاك الموارد للحصول على استجابة محسّنة."
type: docs
weight: 90
url: /ar/net/aspose.imaging.fileformats.emf/emfimage/cachedata/
---
## EmfImage.CacheData method

قم بتخزين البيانات مؤقتًا بكفاءة ومنع التحميل المتكرر من [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/) الأساسي باستخدام هذه الطريقة. عزّز الأداء وسهّل الوصول إلى البيانات في تطبيقك، مع تحسين استهلاك الموارد للحصول على استجابة محسّنة.

```csharp
public override void CacheData()
```

## أمثلة

هذا المثال يوضح كيفية تحميل صورة EMF من ملف وإدراج جميع سجلاتها.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // خزن البيانات مؤقتًا لتحميل جميع السجلات.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // المفتاح هو نوع السجل، والقيمة هي عدد السجلات من ذلك النوع في صورة WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // جمع الإحصائيات 
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

    // طباعة الإحصائيات
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//قد يبدو الإخراج هكذا:
//إجمالي عدد السجلات: 1188
//نوع السجل                              العدد
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### انظر أيضًا

* class [EmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../emfimage/)
* assembly [Aspose.Imaging](../../../)


