---
title: "PdfCoreOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "PDF'ye dönüştürme için ortak seçenekler"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

PDF'ye dönüştürme için ortak seçenekler
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Belge taslağına dahil edilecek taslak öğesi seviyelerinin sayısını belirtir. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Belge taslağına dahil edilecek taslak öğesi seviyelerinin sayısını belirtir. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | PDF dosyası görüntülendiğinde belge taslağında genişletilmiş olarak gösterilecek seviye sayısını belirtir. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | PDF dosyası görüntülendiğinde belge taslağında genişletilmiş olarak gösterilecek seviye sayısını belirtir. |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Belge taslağında yer işareti nesnelerinin hangi seviyede görüntüleneceğini belirtir. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Belge taslağında yer işareti nesnelerinin hangi seviyede görüntüleneceğini belirtir. |
| [getJpegQuality()](#getJpegQuality--) | Görseller için JPEG sıkıştırma kalitesini belirtir (JPEG sıkıştırma kullanılıyorsa). |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Görseller için JPEG sıkıştırma kalitesini belirtir (JPEG sıkıştırma kullanılıyorsa). |
| [getPdfCompliance()](#getPdfCompliance--) | PDF uyumluluğunu alır. |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | PDF uyumluluğunu ayarlar. |
| [getCompression()](#getCompression--) | Sıkıştırmayı alır. |
| [setCompression(int value)](#setCompression-int-) | Sıkıştırmayı ayarlar. |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Belge taslağına dahil edilecek taslak öğesi seviyelerinin sayısını belirtir. 0 - taslak yok, 1 - bir taslak seviyesi vb. Varsayılan 0'dır.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Belge taslağına dahil edilecek taslak öğesi seviyelerinin sayısını belirtir. 0 - taslak yok, 1 - bir taslak seviyesi vb. Varsayılan 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


PDF dosyası görüntülendiğinde belge taslağında genişletilmiş olarak gösterilecek seviye sayısını belirtir. 0 - belge taslağı genişletilmez. 1 - belge içindeki birinci seviye öğeler genişletilir vb. Varsayılan 0'dır.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


PDF dosyası görüntülendiğinde belge taslağında genişletilmiş olarak gösterilecek seviye sayısını belirtir. 0 - belge taslağı genişletilmez. 1 - belge içindeki birinci seviye öğeler genişletilir vb. Varsayılan 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Belge taslağında yer işareti nesnelerinin hangi seviyede görüntüleneceğini belirtir. 0 - görüntülenmez. 1 - birinci seviyede vb. Varsayılan 0'dır.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Belge taslağında yer işareti nesnelerinin hangi seviyede görüntüleneceğini belirtir. 0 - görüntülenmez. 1 - birinci seviyede vb. Varsayılan 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Görseller için JPEG sıkıştırma kalitesini belirtir (JPEG sıkıştırma kullanılıyorsa). Varsayılan 95'tir.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Görseller için JPEG sıkıştırma kalitesini belirtir (JPEG sıkıştırma kullanılıyorsa). Varsayılan 95'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


PDF uyumluluğunu alır.

**Returns:**
int - PDF uyumluluğu.
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


PDF uyumluluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | PDF uyumluluğu. |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Sıkıştırmayı alır.

Değer: Sıkıştırma.

**Returns:**
int - sıkıştırma.
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Sıkıştırmayı ayarlar.

Değer: Sıkıştırma.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | sıkıştırma. |

