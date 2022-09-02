---
title: Records
second_title: Aspose.Imaging for .NET API Referansı
description: Kayıtları alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.emf/metaimage/records/
---
## MetaImage.Records property

Kayıtları alır veya ayarlar.

```csharp
public virtual MetaObjectList Records { get; set; }
```

### Mülk değeri

Kayıtlar.

### Örnekler

Bu örnek, bir dosyadan bir WMF görüntüsünün nasıl yükleneceğini ve tüm kayıtlarının nasıl listelendiğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load'u kullanmak, WMF dahil tüm görüntü türlerini yüklemek için birleşik bir yoldur.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // Tüm kayıtları yüklemek için verileri önbelleğe alın.
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // Anahtar bir kayıt türüdür, değer WMF görüntüsündeki o türden kayıt sayısıdır.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // İstatistikleri topla 
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

    // İstatistikleri yazdır
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

// Çıktı şöyle görünebilir:
//Toplam kayıt sayısı: 613
// Kayıt Tipi Sayısı
//----------------------------------------------------------
//WmfSetBkMode: 1
//WmfSetTextAlign: 1
//WmfSetRop2: 1
//WmfSetWindowOrg: 1
//WmfSetWindowExt: 1
//WmfCreateBrushInDirect: 119
//WmfSelectObject: 240
//WmfCreatePenInDirect: 119
//WmfSetPolyFillMode: 1
//WmfPolyPolygon: 114
//WmfPolyLine: 7
//WmfSetTextColor: 2
//WmfCreateFontInDirect: 2
//WmfExtTextOut: 2
//WmfDibStrechBlt: 1
//WmfEof: 1
```

Bu örnek, bir dosyadan bir EMF görüntüsünün nasıl yükleneceğini ve tüm kayıtlarının nasıl listelendiğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load'u kullanmak, WMF dahil tüm görüntü türlerini yüklemek için birleşik bir yoldur.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // Tüm kayıtları yüklemek için verileri önbelleğe alın.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // Anahtar bir kayıt türüdür, değer WMF görüntüsündeki o türden kayıt sayısıdır.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // İstatistikleri topla 
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

    // İstatistikleri yazdır
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

// Çıktı şöyle görünebilir:
//Toplam kayıt sayısı: 1188
// Kayıt Tipi Sayısı
//----------------------------------------------------------
//EmfMetafileBaşlığı: 1
//EmfSetBkMode: 1
//EmfSetTextAlign: 1
//EmfSetRop2: 1
//EmfSetWorldTransform: 1
//EmfExtSelectClipRgn: 1
//EmfCreateBrushDolaylı: 113
//EmfSelectObject: 240
//EmfCreatePen: 116
//EmfSetPolyFillMode: 1
//EmfBeginYol: 120
//EmfMoveToEx: 122
//EmfPolyBezierTo16: 36
//EmfLineTo: 172
//EmfCloseŞekil: 14
//EmfEndPath: 120
//EmfStrokeAndFillPath: 113
//EmfStrokeYol: 7
//EmfSetTextColor: 2
//EmfExtCreateFontIndirectW: 2
//EmfExtTextOutW: 2
//EmfStretchBlt: 1
//EmfEof: 1
```

### Ayrıca bakınız

* class [MetaObjectList](../../metaobjectlist)
* class [MetaImage](../../metaimage)
* ad alanı [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
