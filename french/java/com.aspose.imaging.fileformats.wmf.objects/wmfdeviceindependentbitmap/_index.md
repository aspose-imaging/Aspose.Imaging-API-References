---
title: "WmfDeviceIndependentBitmap"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet DeviceIndependentBitmap définit une image au format bitmap indépendant du dispositif (DIB)."
type: docs
weight: 27
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

L'objet DeviceIndependentBitmap définit une image au format bitmap indépendant du dispositif (DIB)
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeader()](#getHeader--) | Obtient ou définit soit un objet BitmapCoreHeader (section 2.2.2.2), soit un objet BitmapInfoHeader (section 2.2.2.3) qui spécifie des informations sur l'image. |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Obtient ou définit soit un objet BitmapCoreHeader (section 2.2.2.2), soit un objet BitmapInfoHeader (section 2.2.2.3) qui spécifie des informations sur l'image. |
| [getColorsData()](#getColorsData--) | Obtient ou définit un tableau optionnel composé soit d'objets RGBQuad (section 2.2.2.20), soit d'entiers non signés de 16 bits qui définissent une table de couleurs. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Obtient ou définit un tableau optionnel composé soit d'objets RGBQuad (section 2.2.2.20), soit d'entiers non signés de 16 bits qui définissent une table de couleurs. |
| [getAData()](#getAData--) | Obtient ou définit un tableau d'octets qui définissent l'image. |
| [setAData(byte[] value)](#setAData-byte---) | Obtient ou définit un tableau d'octets qui définissent l'image. |
| [getCachedImage()](#getCachedImage--) | Obtient l'image raster mise en cache. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Définit l'image raster mise en cache. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Obtient ou définit soit un objet BitmapCoreHeader (section 2.2.2.2), soit un objet BitmapInfoHeader (section 2.2.2.3) qui spécifie des informations sur l'image.

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Obtient ou définit soit un objet BitmapCoreHeader (section 2.2.2.2), soit un objet BitmapInfoHeader (section 2.2.2.3) qui spécifie des informations sur l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Obtient ou définit un tableau optionnel composé soit d'objets RGBQuad (section 2.2.2.20), soit d'entiers non signés de 16 bits qui définissent une table de couleurs. La taille et le contenu de ce champ DOIVENT être déterminés à partir de l'enregistrement métafichier ou de l'objet contenant ce DeviceIndependentBitmap et des informations du champ DIBHeaderInfo. Voir l'énumération ColorUsage (section 2.1.1.6) et l'énumération BitCount (section 2.1.1.3) pour des détails supplémentaires.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Obtient ou définit un tableau optionnel composé soit d'objets RGBQuad (section 2.2.2.20), soit d'entiers non signés de 16 bits qui définissent une table de couleurs. La taille et le contenu de ce champ DOIVENT être déterminés à partir de l'enregistrement métafichier ou de l'objet contenant ce DeviceIndependentBitmap et des informations du champ DIBHeaderInfo. Voir l'énumération ColorUsage (section 2.1.1.6) et l'énumération BitCount (section 2.1.1.3) pour des détails supplémentaires.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Obtient ou définit un tableau d'octets qui définissent l'image. La taille et le format de ces données sont déterminés par les informations du champ DIBHeaderInfo.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Obtient ou définit un tableau d'octets qui définissent l'image. La taille et le format de ces données sont déterminés par les informations du champ DIBHeaderInfo.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Obtient l'image raster mise en cache.

Valeur : l'image mise en cache.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Définit l'image raster mise en cache.

Valeur : l'image mise en cache.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

