---
title: "GifPlainTextRenderingBlock"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gif düz metin uzantı bloğu."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Gif düz metin uzantı bloğu. Düz metin uzantısı, metinsel verileri ve bu verileri basit bir biçimde grafik olarak renderlemek için gerekli parametreleri içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Yeni bir `GifPlainTextRenderingBlock` sınıfı örneği başlatır. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Yeni bir `GifPlainTextRenderingBlock` sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Düz metin uzantı etiketi. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Alt bloğun boyutu. |
| [BLOCK_SIZE](#BLOCK-SIZE) | Genel blok boyutu. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Metin ön planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Metin ön planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Metin arka planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Metin arka planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Izgaradaki her hücrenin piksel cinsinden karakter hücresi genişliğini alır veya ayarlar. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Izgaradaki her hücrenin piksel cinsinden karakter hücresi genişliğini alır veya ayarlar. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Izgaradaki her hücrenin piksel cinsinden karakter hücresi yüksekliğini alır veya ayarlar. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Izgaradaki her hücrenin piksel cinsinden karakter hücresi yüksekliğini alır veya ayarlar. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Metin ızgarasının sol konumunu alır veya ayarlar. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Metin ızgarasının sol konumunu alır veya ayarlar. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Metin ızgarasının üst konumunu alır veya ayarlar. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Metin ızgarasının üst konumunu alır veya ayarlar. |
| [getTextGridWidth()](#getTextGridWidth--) | Metin ızgarasının piksel cinsinden genişliğini alır veya ayarlar. |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Metin ızgarasının piksel cinsinden genişliğini alır veya ayarlar. |
| [getTextGridHeight()](#getTextGridHeight--) | Metin ızgarasının piksel cinsinden yüksekliğini alır veya ayarlar. |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Metin ızgarasının piksel cinsinden yüksekliğini alır veya ayarlar. |
| [getPlainTextData()](#getPlainTextData--) | Düz metin verisini alır veya ayarlar. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Düz metin verisini alır veya ayarlar. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Yeni bir `GifPlainTextRenderingBlock` sınıfı örneği başlatır.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Yeni bir `GifPlainTextRenderingBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textGridLeftPosition | int | Metin ızgarasının sol konumu. |
| textGridTopPosition | int | Metin ızgarasının üst konumu. |
| textGridWidth | int | Metin ızgarasının genişliği. |
| textGridHeight | int | Metin ızgarasının yüksekliği. |
| characterCellWidth | byte | Karakter hücresi genişliği. |
| characterCellHeight | byte | Karakter hücresi yüksekliği. |
| textForegroundColorIndex | byte | Ön plan renk dizini. |
| textBackgroundColorIndex | byte | Arka plan renk indeksi. |
| veri | byte[] | Düz metin verisi. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Düz metin uzantı etiketi.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Alt bloğun boyutu.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


Genel blok boyutu.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Metin ön planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar.

Değer: Ön plan renk indeksi.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Metin ön planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar.

Değer: Ön plan renk indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Metin arka planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar.

Değer: Arka plan renk indeksi.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Metin arka planını çizmeye kullanılan küresel renk paletindeki rengin dizinini alır veya ayarlar.

Değer: Arka plan renk indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Izgaradaki her hücrenin piksel cinsinden karakter hücresi genişliğini alır veya ayarlar.

Değer: Karakter hücresi genişliği.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Izgaradaki her hücrenin piksel cinsinden karakter hücresi genişliğini alır veya ayarlar.

Değer: Karakter hücresi genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Izgaradaki her hücrenin piksel cinsinden karakter hücresi yüksekliğini alır veya ayarlar.

Değer: Karakter hücresi yüksekliği.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Izgaradaki her hücrenin piksel cinsinden karakter hücresi yüksekliğini alır veya ayarlar.

Değer: Karakter hücresi yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Metin ızgarasının sol konumunu alır veya ayarlar.

Değer: Metin ızgarası sol konumu.

Bu, mantıksal ekranın sol kenarına göre metin ızgarasının sol kenarının piksel cinsinden sütun numarasıdır.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Metin ızgarasının sol konumunu alır veya ayarlar.

Değer: Metin ızgarası sol konumu.

Bu, mantıksal ekranın sol kenarına göre metin ızgarasının sol kenarının piksel cinsinden sütun numarasıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Metin ızgarasının üst konumunu alır veya ayarlar.

Değer: Metin ızgarası üst konumu.

Bu, mantıksal ekranın üst kenarına göre metin ızgarasının üst kenarının piksel cinsinden satır numarasıdır.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Metin ızgarasının üst konumunu alır veya ayarlar.

Değer: Metin ızgarası üst konumu.

Bu, mantıksal ekranın üst kenarına göre metin ızgarasının üst kenarının piksel cinsinden satır numarasıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Metin ızgarasının piksel cinsinden genişliğini alır veya ayarlar.

Değer: Metin ızgarası genişliği (piksel).

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Metin ızgarasının piksel cinsinden genişliğini alır veya ayarlar.

Değer: Metin ızgarası genişliği (piksel).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Metin ızgarasının piksel cinsinden yüksekliğini alır veya ayarlar.

Değer: Metin ızgarası yüksekliği (piksel).

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Metin ızgarasının piksel cinsinden yüksekliğini alır veya ayarlar.

Değer: Metin ızgarası yüksekliği (piksel).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Düz metin verisini alır veya ayarlar.

Değer: Düz metin verisi.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Düz metin verisini alır veya ayarlar.

Değer: Düz metin verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

