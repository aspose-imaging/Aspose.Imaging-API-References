---
title: CompressedImageData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece una matriz de bytes que especifican la imagen comprimida. El tipo de compresión DEBE determinarse a partir de los propios datos.
type: docs
weight: 20
url: /es/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/compressedimagedata/
---
## EmfPlusCompressedImage.CompressedImageData property

Obtiene o establece una matriz de bytes que especifican la imagen comprimida. El tipo de compresión DEBE determinarse a partir de los propios datos.

```csharp
public byte[] CompressedImageData { get; set; }
```

### Observaciones

Los mapas de bits se especifican mediante objetos EmfPlusBitmap (sección 2.2.2.2). Un objeto EmfPlusCompressedImage DEBE estar presente en el campo BitmapData de un objeto EmfPlusBitmap si se especifica BitmapDataTypeCompressed en su campo Tipo. Este objeto es genérico y se usa para diferentes tipos de datos comprimidos, incluidos:  Formato de archivo de imagen intercambiable (EXIF), como se especifica en [EXIF];  Formato de intercambio de gráficos (GIF), como se especifica en [GIF];  Grupo conjunto de expertos en fotografía (JPEG), como se especifica en [JFIF];  Gráficos de red portátiles (PNG), como especificado en [RFC2083] y [W3C - PNG]; and  Formato de archivo de imagen de etiqueta (TIFF), como se especifica en [RFC3302] y [TIFF].

### Ver también

* class [EmfPlusCompressedImage](../../emfpluscompressedimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluscompressedimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->