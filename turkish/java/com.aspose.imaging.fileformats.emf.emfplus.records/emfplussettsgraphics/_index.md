---
title: "EmfPlusSetTsGraphics"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusSetTSGraphics kaydı, bir terminal sunucu için grafik cihaz bağlamının durumunu belirtir."
type: docs
weight: 67
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

EmfPlusSetTSGraphics kaydı, bir terminal sunucu için grafik cihaz bağlamının durumunu belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusSetTsGraphics` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | [basic vga colors] olup olmadığını gösteren bir değeri alır. |
| [getHavePalette()](#getHavePalette--) | [have palette] olup olmadığını gösteren bir değeri alır. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Çizgi render kalitesini, çizgi anti-aliasing tipini içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Çizgi render kalitesini, çizgi anti-aliasing tipini içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getTextRenderHint()](#getTextRenderHint--) | Metin render kalitesini, metin anti-aliasing tipini içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Metin render kalitesini, metin anti-aliasing tipini içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getCompositingMode()](#getCompositingMode--) | Kaynak renklerin arka plan renkleriyle nasıl birleştirileceğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Kaynak renklerin arka plan renkleriyle nasıl birleştirileceğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getCompositingQuality()](#getCompositingQuality--) | Çizgilere, eğrilere ve doldurulmuş alanların kenarlarına uygulanacak pürüzsüzleştirme derecesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Çizgilere, eğrilere ve doldurulmuş alanların kenarlarına uygulanacak pürüzsüzleştirme derecesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getRenderOriginX()](#getRenderOriginX--) | Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının yatay koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının yatay koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar. |
| [getRenderOriginY()](#getRenderOriginY--) | Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının dikey koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının dikey koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar. |
| [getTextContrast()](#getTextContrast--) | Anti-aliasing ve ClearType metinlerin render edilmesinde kullanılan gama düzeltme değerini belirten 16 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setTextContrast(short value)](#setTextContrast-short-) | Anti-aliasing ve ClearType metinlerin render edilmesinde kullanılan gama düzeltme değerini belirten 16 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getFilterType()](#getFilterType--) | Gerçekleştirilen ölçekleme biçimini, germe ve küçültme dahil, belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setFilterType(byte value)](#setFilterType-byte-) | Gerçekleştirilen ölçekleme biçimini, germe ve küçültme dahil, belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getPixelOffset()](#getPixelOffset--) | Görüntü ve metin oluşturma sürecinin genel kalitesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Görüntü ve metin oluşturma sürecinin genel kalitesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getWorldToDevice()](#getWorldToDevice--) | Dünya uzayından aygıt uzayına dönüşümleri belirten 192-bit EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Dünya uzayından aygıt uzayına dönüşümleri belirten 192-bit EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. |
| [getPalette()](#getPalette--) | İsteğe bağlı EmfPlusPalette nesnesini alır veya ayarlar. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | İsteğe bağlı EmfPlusPalette nesnesini alır veya ayarlar. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


`EmfPlusSetTsGraphics` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Bu değerin [temel vga renkleri] olup olmadığını alır. Ayarlanırsa, palet yalnızca temel VGA renklerini içerir.

Değer: `true` eğer [temel vga renkleri]; aksi takdirde `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Bu değerin [palet var] olup olmadığını alır. Ayarlanırsa, bu kayıt grafik durum verisinin ardından Palette alanında bir EmfPlusPalette nesnesi (bölüm 2.2.2.28) içerir.

Değer: `true` eğer [palet var]; aksi takdirde `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Satır renderleme kalitesini, satır anti-aliasing türünü de içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, SmoothingMode numaralandırmasında (bölüm 2.1.1.28) tanımlanmalıdır.

Değer: Anti-alias modu.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Satır renderleme kalitesini, satır anti-aliasing türünü de içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, SmoothingMode numaralandırmasında (bölüm 2.1.1.28) tanımlanmalıdır.

Değer: Anti-alias modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Metin renderleme kalitesini, metin anti-aliasing türünü de içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, TextRenderingHint numaralandırmasında (bölüm 2.1.1.32) tanımlanmalıdır.

Değer: Metin render ipucu.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Metin renderleme kalitesini, metin anti-aliasing türünü de içerecek şekilde belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, TextRenderingHint numaralandırmasında (bölüm 2.1.1.32) tanımlanmalıdır.

Değer: Metin render ipucu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Kaynak renklerin arka plan renkleriyle nasıl birleştirileceğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, CompositingMode numaralandırmasında (bölüm 2.1.1.5) bir değer olmalıdır.

Değer: Birleştirme modu.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Kaynak renklerin arka plan renkleriyle nasıl birleştirileceğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, CompositingMode numaralandırmasında (bölüm 2.1.1.5) bir değer olmalıdır.

Değer: Birleştirme modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Satırlara, eğrilere ve doldurulmuş alanların kenarlarına uygulanacak yumuşatma derecesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, CompositingQuality numaralandırmasında (bölüm 2.1.1.6) bir değer olmalıdır.

Değer: Kompozisyon kalitesi.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Satırlara, eğrilere ve doldurulmuş alanların kenarlarına uygulanacak yumuşatma derecesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, CompositingQuality numaralandırmasında (bölüm 2.1.1.6) bir değer olmalıdır.

Değer: Kompozisyon kalitesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının yatay koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar.

Değer: Render başlangıç x.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının yatay koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar.

Değer: Render başlangıç x.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının dikey koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar.

Değer: Render başlangıç y.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Yarı tonlama ve dithering matrislerinin render edilmesi için başlangıç noktasının dikey koordinatını belirten 16 bit işaretli tamsayıyı alır veya ayarlar.

Değer: Render başlangıç y.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Anti-alias ve ClearType metin renderlemesi için kullanılan gama düzeltme değerini belirten 16 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer 0 ile 12 arasında (dahil) olmalıdır.

Değer: Metin kontrastı.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Anti-alias ve ClearType metin renderlemesi için kullanılan gama düzeltme değerini belirten 16 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer 0 ile 12 arasında (dahil) olmalıdır.

Değer: Metin kontrastı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Germe ve küçültme dahil ölçeklemenin nasıl gerçekleştirileceğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, FilterType numaralandırmasında (bölüm 2.1.1.11) bir değer olmalıdır.

Değer: Filtre türü.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Germe ve küçültme dahil ölçeklemenin nasıl gerçekleştirileceğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, FilterType numaralandırmasında (bölüm 2.1.1.11) bir değer olmalıdır.

Değer: Filtre türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Görüntü ve metin renderleme sürecinin genel kalitesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, PixelOffsetMode numaralandırmasında (bölüm 2.1.1.26) bir değer olmalıdır.

Değer: Piksel offseti.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Görüntü ve metin renderleme sürecinin genel kalitesini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, PixelOffsetMode numaralandırmasında (bölüm 2.1.1.26) bir değer olmalıdır.

Değer: Piksel offseti.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Dünya uzayından aygıt uzayına dönüşümleri belirten 192-bit EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar.

Değer: Dünya‑cihaz dönüşümü.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Dünya uzayından aygıt uzayına dönüşümleri belirten 192-bit EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar.

Değer: Dünya‑cihaz dönüşümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


İsteğe bağlı EmfPlusPalette nesnesini alır veya ayarlar.

Değer: Palet.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


İsteğe bağlı EmfPlusPalette nesnesini alır veya ayarlar.

Değer: Palet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

