---
title: "EmfPlusCompressedImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusCompressedImage spécifie une image avec des données compressées."
type: docs
weight: 31
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

L'objet EmfPlusCompressedImage spécifie une image avec des données compressées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Obtient ou définit un tableau d'octets qui spécifie l'image compressée. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Obtient ou définit un tableau d'octets qui spécifie l'image compressée. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Obtient ou définit un tableau d'octets qui spécifie l'image compressée. Le type de compression DOIT être déterminé à partir des données elles‑mêmes.

Les bitmaps sont spécifiés par des objets EmfPlusBitmap (section 2.2.2.2). Un objet EmfPlusCompressedImage DOIT être présent dans le champ BitmapData d'un objet EmfPlusBitmap si BitmapDataTypeCompressed est spécifié dans son champ Type. Cet objet est générique et est utilisé pour différents types de données compressées, y compris : \\uf0a7 Exchangeable Image File Format(EXIF), comme spécifié dans [EXIF] ; \\uf0a7 Graphics Interchange Format(GIF), comme spécifié dans [GIF] ; \\uf0a7 Joint Photographic Experts Group(JPEG), comme spécifié dans [JFIF] ; \\uf0a7 Portable Network Graphics(PNG), comme spécifié dans [RFC2083] et [W3C - PNG] ; et \\uf0a7 Tag Image File Format(TIFF), comme spécifié dans [RFC3302] et [TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Obtient ou définit un tableau d'octets qui spécifie l'image compressée. Le type de compression DOIT être déterminé à partir des données elles‑mêmes.

Les bitmaps sont spécifiés par des objets EmfPlusBitmap (section 2.2.2.2). Un objet EmfPlusCompressedImage DOIT être présent dans le champ BitmapData d'un objet EmfPlusBitmap si BitmapDataTypeCompressed est spécifié dans son champ Type. Cet objet est générique et est utilisé pour différents types de données compressées, y compris : \\uf0a7 Exchangeable Image File Format(EXIF), comme spécifié dans [EXIF] ; \\uf0a7 Graphics Interchange Format(GIF), comme spécifié dans [GIF] ; \\uf0a7 Joint Photographic Experts Group(JPEG), comme spécifié dans [JFIF] ; \\uf0a7 Portable Network Graphics(PNG), comme spécifié dans [RFC2083] et [W3C - PNG] ; et \\uf0a7 Tag Image File Format(TIFF), comme spécifié dans [RFC3302] et [TIFF].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

