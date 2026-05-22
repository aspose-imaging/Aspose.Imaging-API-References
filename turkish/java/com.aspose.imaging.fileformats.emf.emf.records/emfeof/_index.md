---
title: "EmfEof"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_EOF kaydı, metafilin sonunu gösterir ve bir palet belirtir."
type: docs
weight: 48
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

EMR_EOF kaydı metafilenin sonunu gösterir ve bir palet belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfEof` sınıfının yeni bir örneğini başlatır. |
| [EmfEof()](#EmfEof--) | `EmfEof` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | EMR\_EOF kaydının sabit kısmıyla bitişik olması gerekmeyen, palet verisi içeren isteğe bağlı bir tamponu alır. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | EMR\_EOF kaydının sabit kısmıyla bitişik olması gerekmeyen, palet verisi içeren isteğe bağlı bir tamponu ayarlar. |
| [getSizeLast()](#getSizeLast--) | Kayıdın ve dolayısıyla metafilin son alanı olması gereken, Size ile aynı olması zorunlu olan 32 bit işaretsiz bir tam sayı alır. |
| [setSizeLast(int value)](#setSizeLast-int-) | Kayıdın ve dolayısıyla metafilin son alanı olması gereken, Size ile aynı olması zorunlu olan 32 bit işaretsiz bir tam sayı ayarlar. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


`EmfEof` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kayıt. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


`EmfEof` sınıfının yeni bir örneğini başlatır.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


EMR\_EOF kaydının sabit kısmıyla bitişik olması gerekmeyen, palet verisi içeren isteğe bağlı bir tamponu alır. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK EDİLMELERİ gerekir. Bu alanın boyutu 4 baytın katı olmak zorundadır.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


EMR\_EOF kaydının sabit kısmıyla bitişik olması gerekmeyen, palet verisi içeren isteğe bağlı bir tamponu ayarlar. Bu nedenle, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK EDİLMELERİ gerekir. Bu alanın boyutu 4 baytın katı olmak zorundadır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Kayıdın ve dolayısıyla metafilin son alanı olması gereken, Size ile aynı olması zorunlu olan 32 bit işaretsiz bir tam sayı alır. LogPaletteEntry nesneleri, mevcutsa, bu alanın önünde yer almalıdır.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Kayıdın ve dolayısıyla metafilin son alanı olması gereken, Size ile aynı olması zorunlu olan 32 bit işaretsiz bir tam sayı ayarlar. LogPaletteEntry nesneleri, mevcutsa, bu alanın önünde yer almalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

