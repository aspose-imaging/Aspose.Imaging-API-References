---
title: EmfDeleteObject
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir örneğini başlatırEmfDeleteObjectaspose.imaging.fileformats.emf.emf.records/emfdeleteobject sınıf.
type: docs
weight: 10
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/emfdeleteobject/
---
## EmfDeleteObject(EmfRecord) {#constructor_1}

Yeni bir örneğini başlatır[`EmfDeleteObject`](../../emfdeleteobject) sınıf.

```csharp
public EmfDeleteObject(EmfRecord record)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| record | EmfRecord | Kayıt. |

### Ayrıca bakınız

* class [EmfRecord](../../emfrecord)
* class [EmfDeleteObject](../../emfdeleteobject)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfdeleteobject)
* toplantı [Aspose.Imaging](../../../)

---

## EmfDeleteObject() {#constructor}

Yeni bir örneğini başlatır[`EmfDeleteObject`](../../emfdeleteobject) sınıf.

```csharp
public EmfDeleteObject()
```

### Örnekler

Aşağıdaki örnek, EMF için arka plan renginin nasıl ayarlandığını gösterir. Aslında, diğer tüm nesneleri çizmeden önce arka plan renginin bir dikdörtgenini koyar.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image1.emf";
string outputFilePath = dir + "ChangeBackground_" + "image1.emf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleEmf((Aspose.Imaging.FileFormats.Emf.EmfImage)image, Aspose.Imaging.Color.Blue);

    image.Save(outputFilePath);
}
    
/// <summary>
/// EMF arka planını değiştirmek için yardımcı yöntem.
/// </summary>
public static void AddBackgroundRectangleEmf(Aspose.Imaging.FileFormats.Emf.EmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    // Dikdörtgeni Ayarla
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle rectangle = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle();
    rectangle.Box = image.Header.EmfHeader.Bounds;

    // Fırçayı Ayarla
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect brush = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    // Nesne dizinleri 1'den başlar; sıfır, meta dosyasının kendisine yapılan başvurular için ayrılmıştır, bkz.
    // https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-emf/e4fa4e63-9096-4cdc-b776-85e2a1e4e1f4
    brush.IhBrush = 1;

    // Fırça seç
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject();
    selectObject.ObjectHandle = 1;

    //Fırçayı kaldır
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject();
    deleteObject.ObjectHandle = 1;

    //Kayıt ekle
    image.Records.Insert(1, brush);
    image.Records.Insert(2, selectObject);
    image.Records.Insert(3, rectangle);
    image.Records.Insert(4, deleteObject);
}
```

### Ayrıca bakınız

* class [EmfDeleteObject](../../emfdeleteobject)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfdeleteobject)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
