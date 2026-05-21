---
title: "EmfCommentWindowsMetaFile"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_COMMENT_WINDOWS_METAFILE kaydı, gömülü bir WMF metafilesinde bir görüntüyü belirtir."
type: docs
weight: 33
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

EMR_COMMENT_WINDOWS_METAFILE kaydı gömülü bir WMF metafilesinde bir görüntüyü belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfCommentWindowsMetaFile` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) | WMF MetafileVersion enumarasyonundan ([MS-WMF] bölüm 2.1.1.19) cihaz bağımsız bitmap (DIB) desteği açısından WMF metafile sürümünü belirten 16-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setVersion(short value)](#setVersion-short-) | WMF MetafileVersion enumarasyonundan ([MS-WMF] bölüm 2.1.1.19) cihaz bağımsız bitmap (DIB) desteği açısından WMF metafile sürümünü belirten 16-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getChecksum()](#getChecksum--) | Bu kayıt için sağlama toplamını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setChecksum(int value)](#setChecksum-int-) | Bu kayıt için sağlama toplamını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getFlags()](#getFlags--) | 0x00000000 olması gereken ve göz ardı edilmesi gereken 32-bit değeri alır veya ayarlar. |
| [setFlags(int value)](#setFlags-int-) | 0x00000000 olması gereken ve göz ardı edilmesi gereken 32-bit değeri alır veya ayarlar. |
| [getWinMetafileSize()](#getWinMetafileSize--) | WinMetafile alanındaki WMF metafilesinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | WinMetafile alanındaki WMF metafilesinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getWinMetafile()](#getWinMetafile--) | WMF metafilesini içeren bir tamponu alır veya ayarlar. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | WMF metafilesini içeren bir tamponu alır veya ayarlar. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


`EmfCommentWindowsMetaFile` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


WMF MetafileVersion enumarasyonundan ([MS-WMF] bölüm 2.1.1.19) cihaz bağımsız bitmap (DIB) desteği açısından WMF metafile sürümünü belirten 16-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


WMF MetafileVersion enumarasyonundan ([MS-WMF] bölüm 2.1.1.19) cihaz bağımsız bitmap (DIB) desteği açısından WMF metafile sürümünü belirten 16-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Bu kayıt için sağlama toplamını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Bu kayıt için sağlama toplamını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


0x00000000 olması gereken ve göz ardı edilmesi gereken 32-bit değeri alır veya ayarlar.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


0x00000000 olması gereken ve göz ardı edilmesi gereken 32-bit değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


WinMetafile alanındaki WMF metafilesinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


WinMetafile alanındaki WMF metafilesinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


WMF metafilesini içeren bir tamponu alır veya ayarlar.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


WMF metafilesini içeren bir tamponu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

