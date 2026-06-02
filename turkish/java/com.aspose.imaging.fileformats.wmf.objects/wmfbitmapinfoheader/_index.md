---
title: "WmfBitmapInfoHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BitmapInfoHeader Nesnesi, cihazdan bağımsız bitmap DIB'in boyutları ve renk biçimi hakkında bilgi içerir."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

BitmapInfoHeader Nesnesi, cihaz bağımsız bitmap (DIB) boyutları ve renk formatı hakkında bilgi içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | Yapı boyutu |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | DIB'in genişliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | DIB'in genişliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [getHeight()](#getHeight--) | DIB'in yüksekliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [setHeight(int value)](#setHeight-int-) | DIB'in yüksekliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [getCompression()](#getCompression--) | DIB'in sıkıştırma modunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setCompression(int value)](#setCompression-int-) | DIB'in sıkıştırma modunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getImageSize()](#getImageSize--) | Görüntünün bayt cinsinden boyutunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setImageSize(int value)](#setImageSize-int-) | Görüntünün bayt cinsinden boyutunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | DIB için hedef cihazın yatay çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | DIB için hedef cihazın yatay çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | DIB için hedef cihazın dikey çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | DIB için hedef cihazın dikey çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. |
| [getColorUsed()](#getColorUsed--) | DIB tarafından kullanılan renk tablosundaki indeks sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar; şu şekilde: Bu değer sıfır ise, DIB BitCount değerine karşılık gelen maksimum renk sayısını kullanır. |
| [setColorUsed(int value)](#setColorUsed-int-) | DIB tarafından kullanılan renk tablosundaki indeks sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar; şu şekilde: Bu değer sıfır ise, DIB BitCount değerine karşılık gelen maksimum renk sayısını kullanır. |
| [getColorImportant()](#getColorImportant--) | DIB'in görüntülenmesi için gerekli renk indeks sayısını tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setColorImportant(int value)](#setColorImportant-int-) | DIB'in görüntülenmesi için gerekli renk indeks sayısını tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


Yapı boyutu

### getWidth() {#getWidth--}
```
public int getWidth()
```


DIB'in genişliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. Bu değer POZITIF olmalıdır. Sıkıştırma değeri JPEG veya PNG biçimini belirtiyorsa, bu alan sıkıştırılmış olmayan görüntü dosyasının genişliğini belirtmelidir.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


DIB'in genişliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. Bu değer POZITIF olmalıdır. Sıkıştırma değeri JPEG veya PNG biçimini belirtiyorsa, bu alan sıkıştırılmış olmayan görüntü dosyasının genişliğini belirtmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


DIB'in yüksekliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. Bu değer sıfır olmamalıdır. Değer pozitif ise, DIB alt‑üst (bottom‑up) bitmap'tir ve kökeni sol‑alt köşededir. Değer negatif ise, DIB üst‑alt (top‑down) bitmap'tir ve kökeni sol‑üst köşededir. Üst‑alt bitmap'ler sıkıştırmayı desteklemez. Sıkıştırma değeri JPEG veya PNG biçimini belirtiyorsa, bu alan sıkıştırılmış olmayan görüntü dosyasının yüksekliğini belirtmelidir.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


DIB'in yüksekliğini piksel cinsinden tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar. Bu değer sıfır olmamalıdır. Değer pozitif ise, DIB alt‑üst (bottom‑up) bitmap'tir ve kökeni sol‑alt köşededir. Değer negatif ise, DIB üst‑alt (top‑down) bitmap'tir ve kökeni sol‑üst köşededir. Üst‑alt bitmap'ler sıkıştırmayı desteklemez. Sıkıştırma değeri JPEG veya PNG biçimini belirtiyorsa, bu alan sıkıştırılmış olmayan görüntü dosyasının yüksekliğini belirtmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


DIB'in sıkıştırma modunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer Sıkıştırma Sıralaması'nda (bölüm 2.1.1.7) yer almalıdır. Yükseklik değeri üst‑alt bitmap'i gösteriyorsa, bu değer sıkıştırılmış bir biçim belirtmemelidir.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


DIB'in sıkıştırma modunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer Sıkıştırma Sıralaması'nda (bölüm 2.1.1.7) yer almalıdır. Yükseklik değeri üst‑alt bitmap'i gösteriyorsa, bu değer sıkıştırılmış bir biçim belirtmemelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


Görüntünün bayt cinsinden boyutunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. Sıkıştırma değeri BI\_RGB ise, bu değer sıfır olmalı ve göz ardı edilmelidir. Sıkıştırma değeri BI\_JPEG veya BI\_PNG ise, bu değer sırasıyla JPEG veya PNG görüntü tamponunun boyutunu belirtmelidir.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


Görüntünün bayt cinsinden boyutunu tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. Sıkıştırma değeri BI\_RGB ise, bu değer sıfır olmalı ve göz ardı edilmelidir. Sıkıştırma değeri BI\_JPEG veya BI\_PNG ise, bu değer sırasıyla JPEG veya PNG görüntü tamponunun boyutunu belirtmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


DIB için hedef cihazın yatay çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


DIB için hedef cihazın yatay çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


DIB için hedef cihazın dikey çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar.

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


DIB için hedef cihazın dikey çözünürlüğünü (piksel/metre) tanımlayan 32-bit işaretli tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


DIB tarafından kullanılan renk tablosundaki indeks sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar; şu şekilde: Bu değer sıfır ise, DIB BitCount değerine karşılık gelen maksimum renk sayısını kullanır. Bu değer sıfırdan farklı ve BitCount değeri 16'dan küçükse, bu değer DIB'in kullandığı renk sayısını belirtir. Bu değer sıfırdan farklı ve BitCount değeri 16 veya daha büyükse, bu değer sistem paletinin performansını optimize etmek için kullanılan renk tablosunun boyutunu belirtir. Not: Bu değer sıfırdan farklı ve BitCount değerine göre olası maksimum renk tablosu boyutundan büyükse, maksimum renk tablosu boyutu varsayılmalıdır.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


DIB tarafından kullanılan renk tablosundaki indeks sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar; şu şekilde: Bu değer sıfır ise, DIB BitCount değerine karşılık gelen maksimum renk sayısını kullanır. Bu değer sıfırdan farklı ve BitCount değeri 16'dan küçükse, bu değer DIB'in kullandığı renk sayısını belirtir. Bu değer sıfırdan farklı ve BitCount değeri 16 veya daha büyükse, bu değer sistem paletinin performansını optimize etmek için kullanılan renk tablosunun boyutunu belirtir. Not: Bu değer sıfırdan farklı ve BitCount değerine göre olası maksimum renk tablosu boyutundan büyükse, maksimum renk tablosu boyutu varsayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


DIB'in görüntülenmesi için gerekli renk indeks sayısını tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer sıfır ise, tüm renk indeksleri gereklidir.

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


DIB'in görüntülenmesi için gerekli renk indeks sayısını tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer sıfır ise, tüm renk indeksleri gereklidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

