---
title: "FileStreamContainer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Dosya akışı işleme için yardımcı."
type: docs
weight: 46
url: /tr/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Dosya akışı işleme için yardımcı.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | `com.aspose.imaging.FileStreamContainer`'dan `System.IO.Stream`'e açık bir dönüşüm gerçekleştirir. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | `com.aspose.imaging.FileStreamContainer`'dan `System.IO.FileStream`'e açık bir dönüşüm gerçekleştirir. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Yeni bir dosya akışı oluşturur. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Mevcut bir dosya akışını açar. |
| [isTemporal()](#isTemporal--) | Akışın geçici olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Akışın geçici olup olmadığını gösteren bir değeri ayarlar. |
| [isCreated()](#isCreated--) | Akışın açıkça oluşturulup oluşturulmadığını gösteren bir değeri alır. |
| [getFilePath()](#getFilePath--) | Dosya yolunu alır. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


`com.aspose.imaging.FileStreamContainer`'dan `System.IO.Stream`'e açık bir dönüşüm gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Dosya akışı kapsayıcısı. |

**Returns:**
com.aspose.ms.System.IO.Stream - Dönüşümün sonucu.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


`com.aspose.imaging.FileStreamContainer`'dan `System.IO.FileStream`'e açık bir dönüşüm gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | Dosya akışı kapsayıcısı. |

**Returns:**
com.aspose.ms.System.IO.FileStream - Dönüşümün sonucu.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Yeni bir dosya akışı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileLocation | java.lang.String | Dosya konumu. |
| isTemporal | boolean | Eğer `true` olarak ayarlanırsa dosya akışı konteyneri geçicidir. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Mevcut bir dosya akışını açar. Dosya akışı mevcut değilse uygun istisna fırlatılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileLocation | java.lang.String | Dosya konumu. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Akışın geçici olup olmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - akış geçici ise `true`; aksi takdirde `false`.

Bir geçici akış, serbest bırakıldığında kendini kaldırır. Akış bellek tabanlıysa bu özellik etkisizdir. Akış, açıkça oluşturulmuşsa geçici veya kalıcı olarak işaretlenebilir; aksi takdirde uygun istisna fırlatılır.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


Akışın geçici olup olmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | `true` akış geçici ise; aksi takdirde `false`. |

Bir geçici akış, serbest bırakıldığında kendini kaldırır. Akış bellek tabanlıysa bu özellik etkisizdir. Akış, açıkça oluşturulmuşsa geçici veya kalıcı olarak işaretlenebilir; aksi takdirde uygun istisna fırlatılır. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


Akışın açıkça oluşturulup oluşturulmadığını gösteren bir değeri alır.

**Returns:**
boolean - akış açıkça oluşturulmuşsa `true`; aksi takdirde `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Dosya yolunu alır.

**Returns:**
java.lang.String - Dosya yolu.
