---
title: "EmfPlusCompressedImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusCompressedImage specifica un'immagine con dati compressi."
type: docs
weight: 31
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

L'oggetto EmfPlusCompressedImage specifica un'immagine con dati compressi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Ottiene o imposta un array di byte, che specifica l'immagine compressa. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Ottiene o imposta un array di byte, che specifica l'immagine compressa. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Ottiene o imposta un array di byte, che specifica l'immagine compressa. Il tipo di compressione DEVE essere determinato dai dati stessi.

Le bitmap sono specificate da oggetti EmfPlusBitmap (sezione 2.2.2.2). Un oggetto EmfPlusCompressedImage DEVE essere presente nel campo BitmapData di un oggetto EmfPlusBitmap se BitmapDataTypeCompressed è specificato nel suo campo Type. Questo oggetto è generico ed è usato per diversi tipi di dati compressi, inclusi: \\uf0a7 Exchangeable Image File Format (EXIF), come specificato in [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), come specificato in [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), come specificato in [JFIF]; \\uf0a7 Portable Network Graphics (PNG), come specificato in [RFC2083] e [W3C - PNG]; e \\uf0a7 Tag Image File Format (TIFF), come specificato in [RFC3302] e [TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Ottiene o imposta un array di byte, che specifica l'immagine compressa. Il tipo di compressione DEVE essere determinato dai dati stessi.

Le bitmap sono specificate da oggetti EmfPlusBitmap (sezione 2.2.2.2). Un oggetto EmfPlusCompressedImage DEVE essere presente nel campo BitmapData di un oggetto EmfPlusBitmap se BitmapDataTypeCompressed è specificato nel suo campo Type. Questo oggetto è generico ed è usato per diversi tipi di dati compressi, inclusi: \\uf0a7 Exchangeable Image File Format (EXIF), come specificato in [EXIF]; \\uf0a7 Graphics Interchange Format (GIF), come specificato in [GIF]; \\uf0a7 Joint Photographic Experts Group (JPEG), come specificato in [JFIF]; \\uf0a7 Portable Network Graphics (PNG), come specificato in [RFC2083] e [W3C - PNG]; e \\uf0a7 Tag Image File Format (TIFF), come specificato in [RFC3302] e [TIFF].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

