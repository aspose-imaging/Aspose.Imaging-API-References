---
title: "EmfPixelFormatDescriptor"
second_title: "Aspose.Imaging for Java API Referansı"
description: "PixelFormatDescriptor nesnesi, EMR_HEADER kayıtları bölüm 2.3.4.2'de, oynatma cihaz bağlamı için çıkış yüzeyinin piksel biçimini belirtmek üzere kullanılabilir."
type: docs
weight: 31
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

PixelFormatDescriptor nesnesi, EMR\_HEADER kayıtlarında (bölüm 2.3.4.2) oynatma aygıt bağlamı için çıkış yüzeyinin piksel formatını belirtmek amacıyla kullanılabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNSize()](#getNSize--) | Bu veri yapısının boyutunu bayt cinsinden belirten 16 bitlik bir tam sayıyı alır veya ayarlar. |
| [setNSize(short value)](#setNSize-short-) | Bu veri yapısının boyutunu bayt cinsinden belirten 16 bitlik bir tam sayıyı alır veya ayarlar. |
| [getNVersion()](#getNVersion--) | 0x0001 olarak ayarlanması gereken 16 bitlik bir tam sayıyı alır veya ayarlar. |
| [setNVersion(short value)](#setNVersion-short-) | 0x0001 olarak ayarlanması gereken 16 bitlik bir tam sayıyı alır veya ayarlar. |
| [getDwFlags()](#getDwFlags--) | Çizim yüzeyine çıkış için kullanılan piksel tamponunun özelliklerini belirten bit bayraklarını alır veya ayarlar. |
| [setDwFlags(int value)](#setDwFlags-int-) | Çizim yüzeyine çıkış için kullanılan piksel tamponunun özelliklerini belirten bit bayraklarını alır veya ayarlar. |
| [getIPixelType()](#getIPixelType--) | PFD\_TYPE\_RGBA 0x00 Piksel biçiminin RGBA olduğu piksel veri tipini alır veya ayarlar. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | PFD\_TYPE\_RGBA 0x00 Piksel biçiminin RGBA olduğu piksel veri tipini alır veya ayarlar. |
| [getCColorBits()](#getCColorBits--) | Alfa bit düzlemleri hariç RGBA piksel tipleri için piksel başına bit sayısını alır veya ayarlar. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Alfa bit düzlemleri hariç RGBA piksel tipleri için piksel başına bit sayısını alır veya ayarlar. |
| [getCRedBits()](#getCRedBits--) | Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemlerinin sayısını belirtir. |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemlerinin sayısını belirtir. |
| [getCRedShift()](#getCRedShift--) | Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemleri için bit cinsinden kaydırma sayısını belirtir. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemleri için bit cinsinden kaydırma sayısını belirtir. |
| [getCGreenBits()](#getCGreenBits--) | Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemlerinin sayısını belirtir. |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemlerinin sayısını belirtir. |
| [getCGreenShift()](#getCGreenShift--) | Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemleri için kaydırma sayısını belirtir. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemleri için kaydırma sayısını belirtir. |
| [getCBlueBits()](#getCBlueBits--) | Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemlerinin sayısını belirtir. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemlerinin sayısını belirtir. |
| [getCBlueShift()](#getCBlueShift--) | Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemleri için kaydırma sayısını belirtir. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemleri için kaydırma sayısını belirtir. |
| [getCAlphaBits()](#getCAlphaBits--) | Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemlerinin sayısını belirtir. |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemlerinin sayısını belirtir. |
| [getCAlphaShift()](#getCAlphaShift--) | Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemleri için kaydırma sayısını belirtir. |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemleri için kaydırma sayısını belirtir. |
| [getCAccumBits()](#getCAccumBits--) | Alır veya ayarlar: Birikim tamponundaki toplam bit düzlemi sayısını belirtir. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Alır veya ayarlar: Birikim tamponundaki toplam bit düzlemi sayısını belirtir. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Alır veya ayarlar: Birikim tamponundaki kırmızı bit düzlemlerinin sayısını belirtir. |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Alır veya ayarlar: Birikim tamponundaki kırmızı bit düzlemlerinin sayısını belirtir. |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Alır veya ayarlar: Birikimdeki yeşil bit düzlemlerinin sayısını belirtir. |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Alır veya ayarlar: Birikimdeki yeşil bit düzlemlerinin sayısını belirtir. |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Alır veya ayarlar: Birikim tamponundaki mavi bit düzlemlerinin sayısını belirtir. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Alır veya ayarlar: Birikim tamponundaki mavi bit düzlemlerinin sayısını belirtir. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Alır veya ayarlar: Birikim tamponundaki alfa bit düzlemlerinin sayısını belirtir. |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Alır veya ayarlar: Birikim tamponundaki alfa bit düzlemlerinin sayısını belirtir. |
| [getCDepthBits()](#getCDepthBits--) | Alır veya ayarlar: Derinlik (z-eksen) tamponunun derinliğini belirtir. |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Alır veya ayarlar: Derinlik (z-eksen) tamponunun derinliğini belirtir. |
| [getCStencilBits()](#getCStencilBits--) | Alır veya ayarlar: Şablon tamponunun derinliğini belirtir. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Alır veya ayarlar: Şablon tamponunun derinliğini belirtir. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Alır veya ayarlar: Yardımcı tamponların sayısını belirtir. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Alır veya ayarlar: Yardımcı tamponların sayısını belirtir. |
| [getILayerType()](#getILayerType--) | Alır veya ayarlar Bu alan MAY yok sayılabilir |
| [setILayerType(byte value)](#setILayerType-byte-) | Alır veya ayarlar Bu alan MAY yok sayılabilir |
| [getBReserved()](#getBReserved--) | Alır veya ayarlar bindirme ve altbindirme düzlemlerinin sayısını belirtir. |
| [setBReserved(byte value)](#setBReserved-byte-) | Alır veya ayarlar bindirme ve altbindirme düzlemlerinin sayısını belirtir. |
| [getDwLayerMask()](#getDwLayerMask--) | Alır veya ayarlar Bu alan MAY yok sayılabilir |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Alır veya ayarlar Bu alan MAY yok sayılabilir |
| [getDwVisibleMask()](#getDwVisibleMask--) | Alır veya ayarlar bir altbindirme düzleminin şeffaf rengini veya indeksini belirtir. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Alır veya ayarlar bir altbindirme düzleminin şeffaf rengini veya indeksini belirtir. |
| [getDwDamageMask()](#getDwDamageMask--) | Alır veya ayarlar Bu alan MAY yok sayılabilir |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Alır veya ayarlar Bu alan MAY yok sayılabilir |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Bu veri yapısının boyutunu bayt cinsinden belirten 16 bitlik bir tam sayıyı alır veya ayarlar.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Bu veri yapısının boyutunu bayt cinsinden belirten 16 bitlik bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


0x0001 olarak ayarlanması gereken 16 bitlik bir tam sayıyı alır veya ayarlar.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


0x0001 olarak ayarlanması gereken 16 bitlik bir tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Alır veya ayarlar piksel tamponunun çizim yüzeyine çıkışı için kullanılan özellikleri belirten bit bayrakları. Bu özelliklerin tümü birbirini dışlamaz; bayrak kombinasyonlarına izin verilir, aksi belirtilmedikçe.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Alır veya ayarlar piksel tamponunun çizim yüzeyine çıkışı için kullanılan özellikleri belirten bit bayrakları. Bu özelliklerin tümü birbirini dışlamaz; bayrak kombinasyonlarına izin verilir, aksi belirtilmedikçe.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Alır veya ayarlar piksel verisinin türünü PFD\_TYPE\_RGBA 0x00 Piksel formatı RGBA'dır. PFD\_TYPE\_COLORINDEX 0x01 Her piksel bir renk tablosundaki indekstir.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Alır veya ayarlar piksel verisinin türünü PFD\_TYPE\_RGBA 0x00 Piksel formatı RGBA'dır. PFD\_TYPE\_COLORINDEX 0x01 Her piksel bir renk tablosundaki indekstir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Alır veya ayarlar RGBA piksel türleri için piksel başına bit sayısını, alfa bit düzlemleri hariç. Renk tablosu pikselleri için, bu her renk tablosu indeksinin boyutudur.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Alır veya ayarlar RGBA piksel türleri için piksel başına bit sayısını, alfa bit düzlemleri hariç. Renk tablosu pikselleri için, bu her renk tablosu indeksinin boyutudur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemleri için bit cinsinden kaydırma sayısını belirtir.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki kırmızı bit düzlemleri için bit cinsinden kaydırma sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemleri için kaydırma sayısını belirtir.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki yeşil bit düzlemleri için kaydırma sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemleri için kaydırma sayısını belirtir.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki mavi bit düzlemleri için kaydırma sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemleri için kaydırma sayısını belirtir.

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Alır veya ayarlar: Her RGBA renk tamponundaki alfa bit düzlemleri için kaydırma sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Alır veya ayarlar: Birikim tamponundaki toplam bit düzlemi sayısını belirtir.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Alır veya ayarlar: Birikim tamponundaki toplam bit düzlemi sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Alır veya ayarlar: Birikim tamponundaki kırmızı bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Alır veya ayarlar: Birikim tamponundaki kırmızı bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Alır veya ayarlar: Birikimdeki yeşil bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Alır veya ayarlar: Birikimdeki yeşil bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Alır veya ayarlar: Birikim tamponundaki mavi bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Alır veya ayarlar: Birikim tamponundaki mavi bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Alır veya ayarlar: Birikim tamponundaki alfa bit düzlemlerinin sayısını belirtir.

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Alır veya ayarlar: Birikim tamponundaki alfa bit düzlemlerinin sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Alır veya ayarlar: Derinlik (z-eksen) tamponunun derinliğini belirtir.

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Alır veya ayarlar: Derinlik (z-eksen) tamponunun derinliğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Alır veya ayarlar: Şablon tamponunun derinliğini belirtir.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Alır veya ayarlar: Şablon tamponunun derinliğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Alır veya ayarlar yardımcı tamponların sayısını belirtir. Yardımcı tamponlar desteklenmez.

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Alır veya ayarlar yardımcı tamponların sayısını belirtir. Yardımcı tamponlar desteklenmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Alır veya ayarlar Bu alan MAY yok sayılabilir

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Alır veya ayarlar Bu alan MAY yok sayılabilir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Alır veya ayarlar bindirme ve altbindirme düzlemlerinin sayısını belirtir. Bit 0'dan 3'e kadar 15'e kadar bindirme düzlemi, bit 4'ten 7'ye kadar 15'e kadar altbindirme düzlemi belirtir.

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Alır veya ayarlar bindirme ve altbindirme düzlemlerinin sayısını belirtir. Bit 0'dan 3'e kadar 15'e kadar bindirme düzlemi, bit 4'ten 7'ye kadar 15'e kadar altbindirme düzlemi belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Alır veya ayarlar Bu alan MAY yok sayılabilir

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Alır veya ayarlar Bu alan MAY yok sayılabilir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Alır veya ayarlar bir altbindirme düzleminin şeffaf rengini veya indeksini belirtir. Piksel türü RGBA olduğunda, dwVisibleMask şeffaf bir RGB renk değeridir. Piksel türü renk indeksi olduğunda, şeffaf bir indeks değeridir.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Alır veya ayarlar bir altbindirme düzleminin şeffaf rengini veya indeksini belirtir. Piksel türü RGBA olduğunda, dwVisibleMask şeffaf bir RGB renk değeridir. Piksel türü renk indeksi olduğunda, şeffaf bir indeks değeridir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Alır veya ayarlar Bu alan MAY yok sayılabilir

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Alır veya ayarlar Bu alan MAY yok sayılabilir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

