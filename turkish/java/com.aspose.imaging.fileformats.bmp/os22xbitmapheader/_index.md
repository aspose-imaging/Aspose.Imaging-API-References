---
title: "Os22XBitmapHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "OS/2 2.x OS22XBITMAPHEADER, diğer adıyla BITMAPCOREHEADER2."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

OS/2 2.x OS22XBITMAPHEADER, diğer adıyla BITMAPCOREHEADER2.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getUnits()](#getUnits--) | Birimleri alır. |
| [getReserved()](#getReserved--) | Ayrılmış olanı alır. |
| [getRecording()](#getRecording--) | Kaydı alır. |
| [getRendering()](#getRendering--) | Renderlamayı alır. |
| [getSize1()](#getSize1--) | size1 değerini alır. |
| [getSize2()](#getSize2--) | size2 değerini alır. |
| [getColorEncoding()](#getColorEncoding--) | Renk kodlamasını alır. |
| [getIdentifier()](#getIdentifier--) | Tanımlayıcıyı alır. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Birimleri alır.

**Returns:**
int - Çözünürlüğü ölçmek için kullanılan birim türü
### getReserved() {#getReserved--}
```
public int getReserved()
```


Ayrılmış olanı alır.

**Returns:**
int - Yapıyı 4 bayt sınırına hizalamak için doldurma
### getRecording() {#getRecording--}
```
public int getRecording()
```


Kaydı alır.

**Returns:**
int - Kayıt algoritması
### getRendering() {#getRendering--}
```
public int getRendering()
```


Renderlamayı alır.

**Returns:**
int - Kullanılan yarım tonlama algoritması
### getSize1() {#getSize1--}
```
public int getSize1()
```


size1 değerini alır.

**Returns:**
int - Yarım tonlama algoritması kullanımı için ayrılmış
### getSize2() {#getSize2--}
```
public int getSize2()
```


size2 değerini alır.

**Returns:**
int - Yarım tonlama algoritması kullanımı için ayrılmış
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Renk kodlamasını alır.

**Returns:**
int - Bit eşlemde kullanılan renk modeli
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Tanımlayıcıyı alır.

**Returns:**
int - Uygulama kullanımı için ayrılmış
