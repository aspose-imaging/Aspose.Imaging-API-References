---
title: "WmfImage.CacheData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة WmfImage. تخزين البيانات مؤقتًا بكفاءة مما يلغي الحاجة إلى تحميل إضافي من DataStreamContainer الأساسي. استخدم هذه الطريقة لتحسين الأداء وتقليل استهلاك الموارد داخل تطبيقك عن طريق تخزين والوصول إلى ذاكرة التخزين المؤقت المحلية."
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.wmf/wmfimage/cachedata/
---
## WmfImage.CacheData method

قم بتخزين البيانات مؤقتًا بكفاءة، مما يلغي الحاجة إلى تحميل إضافي من [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/). استخدم هذه الطريقة لتحسين الأداء وتقليل استهلاك الموارد داخل تطبيقك عن طريق تخزين والوصول إلى ذاكرة التخزين المؤقت المحلية.

```csharp
public override void CacheData()
```

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| NotImplementedException |  |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة WMF من ملف وإدراج جميع سجلاتها.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // خزن البيانات مؤقتًا لتحميل جميع السجلات.
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // المفتاح هو نوع السجل، والقيمة هي عدد السجلات من ذلك النوع في صورة WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // جمع الإحصائيات 
    foreach (Aspose.Imaging.FileFormats.Wmf.Objects.WmfObject obj in wmfImage.Records)
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
//إجمالي عدد السجلات: 613
//نوع السجل                              العدد
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### انظر أيضًا

* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


