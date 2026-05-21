---
title: "GifGraphicsControlBlock"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gif grafik kontrol bloğu."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Gif grafik kontrol bloğu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Yeni bir `GifGraphicsControlBlock` sınıfı örneği başlatır. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Yeni bir `GifGraphicsControlBlock` sınıfı örneği başlatır. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Yeni bir `GifGraphicsControlBlock` sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Blok başlık boyutunu belirtir. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Uzantı etiketi. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Alt blok boyutunu alır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Kare gecikme süresini 1/100 saniye cinsinden alır veya ayarlar. |
| [setDelayTime(int value)](#setDelayTime-int-) | Kare gecikme süresini 1/100 saniye cinsinden alır veya ayarlar. |
| [getFlags()](#getFlags--) | Bayrakları alır veya ayarlar. |
| [setFlags(byte value)](#setFlags-byte-) | Bayrakları alır veya ayarlar. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Şeffaf renk indeksini alır veya ayarlar. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Şeffaf renk indeksini alır veya ayarlar. |
| [getDisposalMethod()](#getDisposalMethod--) | İmha yöntemini alır veya ayarlar. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | İmha yöntemini alır veya ayarlar. |
| [getUserInputExpected()](#getUserInputExpected--) | Kullanıcı girdisinin beklendiğini gösteren bir değeri alır veya ayarlar. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Kullanıcı girdisinin beklendiğini gösteren bir değeri alır veya ayarlar. |
| [hasTransparentColor()](#hasTransparentColor--) | Grafik kontrol bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Grafik kontrol bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Bayrakları oluşturur. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Yeni bir `GifGraphicsControlBlock` sınıfı örneği başlatır.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Yeni bir `GifGraphicsControlBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bayraklar | byte | Bayraklar. |
| delayTime | int | 1/100 saniye cinsinden gecikme süresi. |
| transparentColorIndex | byte | Şeffaf renk indeksi. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Yeni bir `GifGraphicsControlBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| delayTime | int | 1/100 saniye cinsinden gecikme süresi. |
| hasTransparentColor | boolean | eğer `true` olarak ayarlanırsa `transparentColorIndex` geçerlidir. |
| transparentColorIndex | byte | Şeffaf renk indeksi. |
| requiresUserInput | boolean | eğer `true` olarak ayarlanırsa kullanıcı girişi beklenir. |
| disposalMethod | int | İmha yöntemi. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Blok başlık boyutunu belirtir.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Uzantı etiketi.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Alt blok boyutunu alır.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Kare gecikme süresini 1/100 saniye cinsinden alır veya ayarlar.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Kare gecikme süresini 1/100 saniye cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Bayrakları alır veya ayarlar.

Değer: Bayraklar.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Bayrakları alır veya ayarlar.

Değer: Bayraklar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Şeffaf renk indeksini alır veya ayarlar.

Değer: Şeffaf renk indeksi.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Şeffaf renk indeksini alır veya ayarlar.

Değer: Şeffaf renk indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


İmha yöntemini alır veya ayarlar.

Değer: İmha yöntemi.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


İmha yöntemini alır veya ayarlar.

Değer: İmha yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Kullanıcı girdisinin beklendiğini gösteren bir değeri alır veya ayarlar.

Değer: kullanıcı girişi bekleniyorsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Kullanıcı girdisinin beklendiğini gösteren bir değeri alır veya ayarlar.

Değer: kullanıcı girişi bekleniyorsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Grafik kontrol bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır veya ayarlar.

Değer: grafik kontrol bloğu şeffaf renk içeriyorsa `true`; aksi takdirde `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Grafik kontrol bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır veya ayarlar.

Değer: grafik kontrol bloğu şeffaf renk içeriyorsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Bayrakları oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hasTransparentColor | boolean | eğer `true` olarak ayarlanırsa `GifGraphicsControlBlock` geçerli şeffaf renk indeksine sahiptir. |
| requiresUserInput | boolean | eğer `true` olarak ayarlanırsa kullanıcı girişi beklenir. |
| disposalMethod | int | İmha yöntemi. |

**Returns:**
byte - Oluşturulan bayraklar.
