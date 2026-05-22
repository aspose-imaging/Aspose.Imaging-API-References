---
title: "Classe WmfDeviceIndependentBitmap"
type: docs
weight: 180
url: /fr/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | Initialise une nouvelle instance de la classe WmfDeviceIndependentBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Obtient ou définit un tableau d'octets qui définit l'image. La taille et<br/>                le format de ces données sont déterminés par les informations dans le<br/>                champ DIBHeaderInfo. |
| cached_image | System.Byte | r/w | Obtient ou définit l'image raster mise en cache. |
| colors_data | System.Byte | r/w | Obtient ou définit un tableau facultatif soit d'objets RGBQuad (section<br/>                2.2.2.20) soit d'entiers non signés de 16 bits qui définissent une table de couleurs. La<br/>                taille et le contenu de ce champ DOIVENT être déterminés à partir de l'enregistrement<br/>                metafile ou de l'objet qui contient ce DeviceIndependentBitmap<br/>                et des informations dans le champ DIBHeaderInfo. Voir l'énumération ColorUsage<br/>                (section 2.1.1.6) et l'énumération BitCount (section<br/>                2.1.1.3) pour des détails supplémentaires |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Obtient ou définit soit un objet BitmapCoreHeader (section 2.2.2.2) soit un<br/>                objet BitmapInfoHeader (section 2.2.2.3) qui spécifie les informations<br/>                sur l'image |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

Initialise une nouvelle instance de la classe WmfDeviceIndependentBitmap

