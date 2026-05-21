---
title: "EmfPlusCompressedImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusCompressedImage especifica una imagen con datos comprimidos."
type: docs
weight: 31
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

El objeto EmfPlusCompressedImage especifica una imagen con datos comprimidos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Obtiene o establece una matriz de bytes, que especifica la imagen comprimida. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Obtiene o establece una matriz de bytes, que especifica la imagen comprimida. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Obtiene o establece una matriz de bytes, que especifica la imagen comprimida. El tipo de compresión DEBE determinarse a partir de los propios datos.

Los mapas de bits son especificados por objetos EmfPlusBitmap (sección 2.2.2.2). Un objeto EmfPlusCompressedImage DEBE estar presente en el campo BitmapData de un objeto EmfPlusBitmap si BitmapDataTypeCompressed está especificado en su campo Type. Este objeto es genérico y se utiliza para diferentes tipos de datos comprimidos, incluyendo: \\uf0a7 Exchangeable Image File Format (EXIF), como se especifica en [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), como se especifica en [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), como se especifica en [JFIF]; \\uf0a7 Portable Network Graphics (PNG), como se especifica en [RFC2083] y [W3C - PNG]; y \\uf0a7 Tag Image File Format (TIFF), como se especifica en [RFC3302] y [TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Obtiene o establece una matriz de bytes, que especifica la imagen comprimida. El tipo de compresión DEBE determinarse a partir de los propios datos.

Los mapas de bits son especificados por objetos EmfPlusBitmap (sección 2.2.2.2). Un objeto EmfPlusCompressedImage DEBE estar presente en el campo BitmapData de un objeto EmfPlusBitmap si BitmapDataTypeCompressed está especificado en su campo Type. Este objeto es genérico y se utiliza para diferentes tipos de datos comprimidos, incluyendo: \\uf0a7 Exchangeable Image File Format (EXIF), como se especifica en [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), como se especifica en [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), como se especifica en [JFIF]; \\uf0a7 Portable Network Graphics (PNG), como se especifica en [RFC2083] y [W3C - PNG]; y \\uf0a7 Tag Image File Format (TIFF), como se especifica en [RFC3302] y [TIFF].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

