---
title: "EmfGlsBoundedRecord"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_GLSBOUNDEDRECORD kaydı, çıktı için bir sınırlayıcı dikdörtgen içeren bir OpenGL işlevini belirtir."
type: docs
weight: 63
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

EMR\_GLSBOUNDEDRECORD kaydı, çıktı için sınırlayıcı bir dikdörtgen içeren bir OpenGL işlevi belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfGlsBoundedRecord` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | OpenGL işlevi yürütülerek üretilen çıktı için cihaz birimlerinde bir sınırlayıcı dikdörtgen tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | OpenGL işlevi yürütülerek üretilen çıktı için cihaz birimlerinde bir sınırlayıcı dikdörtgen tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [getCbData()](#getCbData--) | Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [setCbData(int value)](#setCbData-int-) | Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz bir tamsayı alır veya ayarlar. |
| [getData()](#getData--) | OpenGL işlevi için veriyi belirten, cbData uzunluğunda isteğe bağlı bir bayt dizisi alır veya ayarlar. |
| [setData(byte[] value)](#setData-byte---) | OpenGL işlevi için veriyi belirten, cbData uzunluğunda isteğe bağlı bir bayt dizisi alır veya ayarlar. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Yeni bir `EmfGlsBoundedRecord` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


OpenGL işlevi yürütülerek üretilen çıktı için cihaz birimlerinde bir sınırlayıcı dikdörtgen tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


OpenGL işlevi yürütülerek üretilen çıktı için cihaz birimlerinde bir sınırlayıcı dikdörtgen tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

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

