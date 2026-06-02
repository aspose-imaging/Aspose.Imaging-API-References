---
title: "FileOpenSource"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Açma için bir dosya kaynağını temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Açma için bir dosya kaynağını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Yeni bir `FileOpenSource` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFilePath()](#getFilePath--) | Açılacak dosya yolunu alır. |
| [isTemporal()](#isTemporal--) | Dosyanın geçici olup olmayacağını gösteren bir değeri alır. |
| [getStreamContainer()](#getStreamContainer--) | Akış konteynerini alır. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Yeni bir `FileOpenSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Açılacak dosya yolu. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Açılacak dosya yolunu alır.

Değer: Açılacak dosya yolu.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Dosyanın geçici olup olmayacağını gösteren bir değeri alır.

Değer: Dosya geçici olacaksa `true`; aksi takdirde `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Akış konteynerini alır.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Dikkatli kullanın. Alımdan sonra akış konteynerini serbest bırakmanız gerekir.
