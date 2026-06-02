---
title: "WmfEscapeEnhancedMetafile"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Escape Geliştirilmiş Meta dosya kaydı."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

Escape Geliştirilmiş Meta dosya kaydı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Yorum tanımlayıcısını alır veya ayarlar. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Yorum tanımlayıcısını alır veya ayarlar. |
| [getCommentType()](#getCommentType--) | Yorumun türünü alır veya ayarlar. |
| [setCommentType(int value)](#setCommentType-int-) | Yorumun türünü alır veya ayarlar. |
| [getVersion()](#getVersion--) | sürümü alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | sürümü alır veya ayarlar. |
| [getChecksum()](#getChecksum--) | Sağlama toplamını alır veya ayarlar. |
| [setChecksum(int value)](#setChecksum-int-) | Sağlama toplamını alır veya ayarlar. |
| [getFlags()](#getFlags--) | Bayrakları alır veya ayarlar. |
| [setFlags(int value)](#setFlags-int-) | Bayrakları alır veya ayarlar. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Yorum kaydı sayısını alır veya ayarlar. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Yorum kaydı sayısını alır veya ayarlar. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Geçerli kaydın boyutunu alır veya ayarlar. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Geçerli kaydın boyutunu alır veya ayarlar. |
| [getRemainingBytes()](#getRemainingBytes--) | Kalan baytları alır veya ayarlar. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Kalan baytları alır veya ayarlar. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Gelişmiş metafile verisinin boyutunu alır veya ayarlar. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Gelişmiş metafile verisinin boyutunu alır veya ayarlar. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Gelişmiş metafile verisini alır veya ayarlar. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Gelişmiş metafile verisini alır veya ayarlar. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Yorum tanımlayıcısını alır veya ayarlar.

Value: Bu kaydı bir WMF Yorum kaydı olarak tanımlayan 32 bit işaretsiz tamsayı. Bu değer 0x43464D57 OLMALIDIR.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Yorum tanımlayıcısını alır veya ayarlar.

Value: Bu kaydı bir WMF Yorum kaydı olarak tanımlayan 32 bit işaretsiz tamsayı. Bu değer 0x43464D57 OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Yorumun türünü alır veya ayarlar.

Value: Bu kayıttaki yorum türünü belirleyen 32 bit işaretsiz tamsayı. Bu değer 0x00000001 OLMALIDIR.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Yorumun türünü alır veya ayarlar.

Value: Bu kayıttaki yorum türünü belirleyen 32 bit işaretsiz tamsayı. Bu değer 0x00000001 OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


sürümü alır veya ayarlar.

Value: EMF metafile birlikte çalışabilirliğini belirten 32 bit işaretsiz tamsayı. Bu 0x00010000 OLMALIDIR.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


sürümü alır veya ayarlar.

Value: EMF metafile birlikte çalışabilirliğini belirten 32 bit işaretsiz tamsayı. Bu 0x00010000 OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Sağlama toplamını alır veya ayarlar.

Value: Gömülü EMF akışının doğruluğunu doğrulamak için kullanılan 16 bit işaretsiz tamsayı. Bu değer, EMF akışındaki tüm WORD'lara XOR işlemi uygulanmasının sonucunun bir'in tamamı OLMALIDIR.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Sağlama toplamını alır veya ayarlar.

Value: Gömülü EMF akışının doğruluğunu doğrulamak için kullanılan 16 bit işaretsiz tamsayı. Bu değer, EMF akışındaki tüm WORD'lara XOR işlemi uygulanmasının sonucunun bir'in tamamı OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Bayrakları alır veya ayarlar.

Value: Bu 32 bit işaretsiz tamsayı kullanılmaz ve sıfır olarak ayarlanmalıdır.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Bayrakları alır veya ayarlar.

Value: Bu 32 bit işaretsiz tamsayı kullanılmaz ve sıfır olarak ayarlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Yorum kaydı sayısını alır veya ayarlar.

Value: Gömülü EMF metafilesini içeren ardışık META_ESCAPE_ENHANCED_METAFILE kayıtlarının toplam sayısını belirten 32 bit işaretsiz tamsayı.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Yorum kaydı sayısını alır veya ayarlar.

Value: Gömülü EMF metafilesini içeren ardışık META_ESCAPE_ENHANCED_METAFILE kayıtlarının toplam sayısını belirten 32 bit işaretsiz tamsayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Geçerli kaydın boyutunu alır veya ayarlar.

Value: EnhancedMetafileData alanının bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayı. Bu değer 8.192'ye eşit veya daha küçük OLMALIDIR.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Geçerli kaydın boyutunu alır veya ayarlar.

Value: EnhancedMetafileData alanının bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayı. Bu değer 8.192'ye eşit veya daha küçük OLMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Kalan baytları alır veya ayarlar.

Value: Bu kayıttan sonra işlenmesi kalan EMF akışındaki bayt sayısını belirten 32 bit işaretsiz tamsayı. Bu ek EMF baytları, sonraki META_ESCAPE_ENHANDED_METAFILE kaçış kayıtlarının EnhancedMetafileData alanlarında izlemelidir.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Kalan baytları alır veya ayarlar.

Value: Bu kayıttan sonra işlenmesi kalan EMF akışındaki bayt sayısını belirten 32 bit işaretsiz tamsayı. Bu ek EMF baytları, sonraki META_ESCAPE_ENHANDED_METAFILE kaçış kayıtlarının EnhancedMetafileData alanlarında izlemelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Gelişmiş metafile verisinin boyutunu alır veya ayarlar.

Value: Bu META_ESCAPE_ENHANCED_METAFILE kayıtları dizisine gömülmüş EMF akışının toplam boyutunu belirten 32 bit işaretsiz tamsayı.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Gelişmiş metafile verisinin boyutunu alır veya ayarlar.

Value: Bu META_ESCAPE_ENHANCED_METAFILE kayıtları dizisine gömülmüş EMF akışının toplam boyutunu belirten 32 bit işaretsiz tamsayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Gelişmiş metafile verisini alır veya ayarlar.

Value: Bir EMF dosyasının bölümü. Ardışık META_ESCAPE_ENHANCED_METAFILE kayıtlarındaki baytlar, gömülü EMF dosyasının tamamını temsil edecek şekilde birleştirilmelidir.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Gelişmiş metafile verisini alır veya ayarlar.

Value: Bir EMF dosyasının bölümü. Ardışık META_ESCAPE_ENHANCED_METAFILE kayıtlarındaki baytlar, gömülü EMF dosyasının tamamını temsil edecek şekilde birleştirilmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

