---
title: "EmfGlsRecord"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_GLSRECORD kaydı bir OpenGL işlevini belirtir."
type: docs
weight: 64
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

EMR\_GLSRECORD kaydı, bir OpenGL işlevi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfGlsRecord` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCbData()](#getCbData--) | Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [setCbData(int value)](#setCbData-int-) | Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [getData()](#getData--) | OpenGL işlevi için veriyi belirten, cbData uzunluğunda isteğe bağlı bir bayt dizisi alır veya ayarlar. |
| [setData(byte[] value)](#setData-byte---) | OpenGL işlevi için veriyi belirten, cbData uzunluğunda isteğe bağlı bir bayt dizisi alır veya ayarlar. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


`EmfGlsRecord` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu değer sıfır ise, bu kayda veri eklenmez.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu değer sıfır ise, bu kayda veri eklenmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


OpenGL işlevi için veriyi belirten, cbData uzunluğunda isteğe bağlı bir bayt dizisi alır veya ayarlar.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


OpenGL işlevi için veriyi belirten, cbData uzunluğunda isteğe bağlı bir bayt dizisi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

