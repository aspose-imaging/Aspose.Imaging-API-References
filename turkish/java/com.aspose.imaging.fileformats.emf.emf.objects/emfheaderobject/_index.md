---
title: "EmfHeaderObject"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Header nesnesi, EMF metafile başlığını tanımlar."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

Header nesnesi EMF metafile başlığını tanımlar. Metafile içindeki görüntünün oluşturulduğu cihazın özelliklerini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | `EmfHeaderObject` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Metafile içinde depolanan görüntünün etrafına çizilebilecek en küçük dikdörtgenin cihaz birimlerindeki kapsayıcı‑kapsayıcı sınırlarını belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Metafile içinde depolanan görüntünün etrafına çizilebilecek en küçük dikdörtgenin cihaz birimlerindeki kapsayıcı‑kapsayıcı sınırlarını belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar |
| [getFrame()](#getFrame--) | Metafile içinde depolanan görüntüyü çevreleyen bir dikdörtgenin .01 milimetre birimlerindeki kapsayıcı‑kapsayıcı boyutlarını belirten bir WMF RectL nesnesini alır veya ayarlar |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Metafile içinde depolanan görüntüyü çevreleyen bir dikdörtgenin .01 milimetre birimlerindeki kapsayıcı‑kapsayıcı boyutlarını belirten bir WMF RectL nesnesini alır veya ayarlar |
| [getRecordSignature()](#getRecordSignature--) | Kayıt imzasını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Kayıt imzasını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getVersion()](#getVersion--) | Version (4 bayt) alır veya ayarlar: EMF metafile birlikte çalışabilirliğini belirten 32 bit işaretsiz bir tam sayı. |
| [setVersion(int value)](#setVersion-int-) | Version (4 bayt) alır veya ayarlar: EMF metafile birlikte çalışabilirliğini belirten 32 bit işaretsiz bir tam sayı. |
| [getBytes()](#getBytes--) | Metafile boyutunu bayt cinsinden belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setBytes(int value)](#setBytes-int-) | Metafile boyutunu bayt cinsinden belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getRecords()](#getRecords--) | Metafile içindeki kayıt sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setRecords(int value)](#setRecords-int-) | Metafile içindeki kayıt sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getHandles()](#getHandles--) | Metafile işlenmesi sırasında kullanılacak grafik nesnelerinin sayısını belirten 16 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setHandles(short value)](#setHandles-short-) | Metafile işlenmesi sırasında kullanılacak grafik nesnelerinin sayısını belirten 16 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getReserved()](#getReserved--) | 0x0000 olmalı ve göz ardı edilmesi gereken 16 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setReserved(short value)](#setReserved-short-) | 0x0000 olmalı ve göz ardı edilmesi gereken 16 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getNDesription()](#getNDesription--) | Metafile içeriğinin açıklamasını içeren dizideki karakter sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setNDesription(int value)](#setNDesription-int-) | Metafile içeriğinin açıklamasını içeren dizideki karakter sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getOffDescription()](#getOffDescription--) | Bu kaydın başlangıcından metafile içeriğinin açıklamasını içeren diziye olan offseti belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setOffDescription(int value)](#setOffDescription-int-) | Bu kaydın başlangıcından metafile içeriğinin açıklamasını içeren diziye olan offseti belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getNPalEntries()](#getNPalEntries--) | Metafile paletindeki giriş sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Metafile paletindeki giriş sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| [getDevice()](#getDevice--) | Referans cihazın piksel cinsinden boyutunu belirten bir WMF SizeL nesnesini ([MS-WMF] bölüm 2.2.2.22) alır veya ayarlar. |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Referans cihazın piksel cinsinden boyutunu belirten bir WMF SizeL nesnesini ([MS-WMF] bölüm 2.2.2.22) alır veya ayarlar. |
| [getMillimeters()](#getMillimeters--) | Referans cihazın milimetre cinsinden boyutunu belirten bir WMF SizeL nesnesini alır veya ayarlar. |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Referans cihazın milimetre cinsinden boyutunu belirten bir WMF SizeL nesnesini alır veya ayarlar. |
| [getValid()](#getValid--) | Bu `EmfHeaderObject`'in geçerli olup olmadığını gösteren bir değeri alır. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


`EmfHeaderObject` sınıfının yeni bir örneğini başlatır.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Metafile içinde depolanan görüntünün etrafına çizilebilecek en küçük dikdörtgenin cihaz birimlerindeki kapsayıcı‑kapsayıcı sınırlarını belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Metafile içinde depolanan görüntünün etrafına çizilebilecek en küçük dikdörtgenin cihaz birimlerindeki kapsayıcı‑kapsayıcı sınırlarını belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Metafile içinde depolanan görüntüyü çevreleyen bir dikdörtgenin .01 milimetre birimlerindeki kapsayıcı‑kapsayıcı boyutlarını belirten bir WMF RectL nesnesini alır veya ayarlar

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Metafile içinde depolanan görüntüyü çevreleyen bir dikdörtgenin .01 milimetre birimlerindeki kapsayıcı‑kapsayıcı boyutlarını belirten bir WMF RectL nesnesini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Kayıt imzasını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Bu, FormatSignature enumarasyonundan (bölüm 2.1.14) ENHMETA\_SIGNATURE olmalıdır.

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Kayıt imzasını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Bu, FormatSignature enumarasyonundan (bölüm 2.1.14) ENHMETA\_SIGNATURE olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Version (4 bayt) alır veya ayarlar: EMF metafile birlikte çalışabilirliğini belirten 32 bit işaretsiz bir tam sayı. Bu 0x00010000 olmalıdır.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Version (4 bayt) alır veya ayarlar: EMF metafile birlikte çalışabilirliğini belirten 32 bit işaretsiz bir tam sayı. Bu 0x00010000 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Metafile boyutunu bayt cinsinden belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Metafile boyutunu bayt cinsinden belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Metafile içindeki kayıt sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Metafile içindeki kayıt sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Metafile işlenmesi sırasında kullanılacak grafik nesnelerinin sayısını belirten 16 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Metafile işlenmesi sırasında kullanılacak grafik nesnelerinin sayısını belirten 16 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


0x0000 olmalı ve göz ardı edilmesi gereken 16 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


0x0000 olmalı ve göz ardı edilmesi gereken 16 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Metafile içeriğinin açıklamasını içeren dizideki karakter sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Açıklama dizesi yoksa bu sıfırdır.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Metafile içeriğinin açıklamasını içeren dizideki karakter sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Açıklama dizesi yoksa bu sıfırdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Bu kaydın başlangıcından metafile içeriğinin açıklamasını içeren diziye olan offseti belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Bu kaydın başlangıcından metafile içeriğinin açıklamasını içeren diziye olan offseti belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Metafile paletindeki giriş sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Palet EMR\_EOF kaydında bulunur.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Metafile paletindeki giriş sayısını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Palet EMR\_EOF kaydında bulunur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Referans cihazın piksel cinsinden boyutunu belirten bir WMF SizeL nesnesini ([MS-WMF] bölüm 2.2.2.22) alır veya ayarlar.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Referans cihazın piksel cinsinden boyutunu belirten bir WMF SizeL nesnesini ([MS-WMF] bölüm 2.2.2.22) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Referans cihazın milimetre cinsinden boyutunu belirten bir WMF SizeL nesnesini alır veya ayarlar.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Referans cihazın milimetre cinsinden boyutunu belirten bir WMF SizeL nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Bu `EmfHeaderObject`'in geçerli olup olmadığını gösteren bir değeri alır.

Değer: `true` if valid; otherwise, `false`.

**Returns:**
boolean
