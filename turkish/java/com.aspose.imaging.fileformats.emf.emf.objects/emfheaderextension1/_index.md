---
title: "EmfHeaderExtension1"
second_title: "Aspose.Imaging for Java API Referansı"
description: "HeaderExtension1 nesnesi, EMF metafile başlığının ilk uzantısını tanımlar."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

HeaderExtension1 nesnesi, EMF metafile başlığının ilk uzantısını tanımlar. Bir PixelFormatDescriptor nesnesi (bölüm 2.2.22) ve OpenGL [OPENGL] kayıtları (bölüm 2.3.9) için destek ekler.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | PixelFormatDescriptor nesnesinin boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | PixelFormatDescriptor nesnesinin boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getOffPixelFormat()](#getOffPixelFormat--) | PixelFormatDescriptor nesnesine olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | PixelFormatDescriptor nesnesine olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getBOpenGl()](#getBOpenGl--) | Metafile içinde OpenGL komutlarının bulunup bulunmadığını gösteren 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Metafile içinde OpenGL komutlarının bulunup bulunmadığını gösteren 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


PixelFormatDescriptor nesnesinin boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Piksel formatı ayarlanmamışsa bu DEĞİŞMEZ 0x00000000 olmalıdır.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


PixelFormatDescriptor nesnesinin boyutunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Piksel formatı ayarlanmamışsa bu DEĞİŞMEZ 0x00000000 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


PixelFormatDescriptor nesnesine olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Piksel formatı ayarlanmamışsa bu DEĞİŞMEZ 0x00000000 olmalıdır.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


PixelFormatDescriptor nesnesine olan offseti belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Piksel formatı ayarlanmamışsa bu DEĞİŞMEZ 0x00000000 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Metafile içinde OpenGL komutlarının bulunup bulunmadığını gösteren 32 bit işaretsiz tam sayıyı alır veya ayarlar. 0x00000000 OpenGL kayıtları metafilde bulunmaz. 0x00000001 OpenGL kayıtları metafilde bulunur.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Metafile içinde OpenGL komutlarının bulunup bulunmadığını gösteren 32 bit işaretsiz tam sayıyı alır veya ayarlar. 0x00000000 OpenGL kayıtları metafilde bulunmaz. 0x00000001 OpenGL kayıtları metafilde bulunur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

