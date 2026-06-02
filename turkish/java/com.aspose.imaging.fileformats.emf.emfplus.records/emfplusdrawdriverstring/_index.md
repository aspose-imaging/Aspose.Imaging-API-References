---
title: "EmfPlusDrawDriverString"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawDriverString kaydı karakter konumlarıyla metin çıktısını belirtir."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

EmfPlusDrawDriverString kaydı karakter konumlarıyla metin çıktısını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusDrawDriverString` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını ayarlar. |
| [getBrushId()](#getBrushId--) | Fırça tanımlayıcısını alır. Flags içindeki S bayrağının değerine bağlı olarak metnin ön plan rengini veya bir grafik fırçasını belirten 32 bit işaretsiz tam sayı. |
| [setBrushId(int value)](#setBrushId-int-) | Fırça tanımlayıcısını ayarlar 32 bit işaretsiz tamsayı, metnin ön plan rengini veya bir grafik fırçasını belirtir, Flags içindeki S bayrağının değerine bağlı olarak. |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Sürücü dize seçenek bayraklarını alır 32 bit işaretsiz tamsayı, dize için aralık, yönelim ve render kalitesini belirtir. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Sürücü dize seçenek bayraklarını ayarlar 32 bit işaretsiz tamsayı, dize için aralık, yönelim ve render kalitesini belirtir. |
| [getGlyphCount()](#getGlyphCount--) | Glyph sayısını alır 32 bit işaretsiz tamsayı, dizedeki glyph sayısını belirtir. |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Glyph sayısını ayarlar 32 bit işaretsiz tamsayı, dizedeki glyph sayısını belirtir. |
| [getGlyphPos()](#getGlyphPos--) | Glyph konumları dizisini alır EmfPlusPointF nesnelerinin (bölüm 2.2.2.36) bir dizisi, her karakter glyph'inin çıktı konumunu belirtir. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Glyph konumları dizisini ayarlar EmfPlusPointF nesnelerinin (bölüm 2.2.2.36) bir dizisi, her karakter glyph'inin çıktı konumunu belirtir. |
| [getGlyphs()](#getGlyphs--) | Glyph'ler dizisini alır 16 bit değerlerin bir dizisi, çizilecek metin dizesini tanımlar. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Glyph'ler dizisini ayarlar 16 bit değerlerin bir dizisi, çizilecek metin dizesini tanımlar. |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri ayarlar. |
| [getMatrixPresent()](#getMatrixPresent--) | Matrix mevcut bayrağını alır 32 bit işaretsiz tamsayı, TransformMatrix alanında bir dönüşüm matrisi olup olmadığını belirtir 0 - matris yok. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Matrix mevcut bayrağını ayarlar 32 bit işaretsiz tamsayı, TransformMatrix alanında bir dönüşüm matrisi olup olmadığını belirtir 0 - matris yok. |
| [getTransformMatrix()](#getTransformMatrix--) | Dönüşüm matrisini alır İsteğe bağlı EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47), metin dizisindeki her değere uygulanacak dönüşümü belirtir. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Dönüşüm matrisini ayarlar İsteğe bağlı EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47), metin dizisindeki her değere uygulanacak dönüşümü belirtir. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


`EmfPlusDrawDriverString` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır. Metni renderlemek için bir `` nesnesinin EMF+ Object Table indeksidir (bölüm 2.2.1.3). Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

**Returns:**
byte - Nesne tanımlayıcısı.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını ayarlar. Metni renderlemek için bir `` nesnesinin EMF+ Object Table indeksidir (bölüm 2.2.1.3). Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | Nesne tanımlayıcısı. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Fırça tanımlayıcısını alır. Flags içindeki S bayrağının değerine bağlı olarak metnin ön plan rengini veya bir grafik fırçasını belirten 32 bit işaretsiz tam sayı.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Fırça tanımlayıcısını ayarlar 32 bit işaretsiz tamsayı, metnin ön plan rengini veya bir grafik fırçasını belirtir, Flags içindeki S bayrağının değerine bağlı olarak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Sürücü dize seçenek bayraklarını alır 32 bit işaretsiz tamsayı, dize için aralık, yönelim ve render kalitesini belirtir.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Sürücü dize seçenek bayraklarını ayarlar 32 bit işaretsiz tamsayı, dize için aralık, yönelim ve render kalitesini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Glyph sayısını alır 32 bit işaretsiz tamsayı, dizedeki glyph sayısını belirtir.

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Glyph sayısını ayarlar 32 bit işaretsiz tamsayı, dizedeki glyph sayısını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Glyph konumları dizisini alır EmfPlusPointF nesnelerinin (bölüm 2.2.2.36) bir dizisi, her karakter glyph'inin çıktı konumunu belirtir. GlyphCount öğeleri bulunmalıdır, bu öğeler Glyphs dizisindeki öğelerle bire bir eşleşir. DriverStringOptions bayraklarındaki DriverStringOptionsRealizedAdvance bayrağı ayarlıysa, glyph konumları ilk glyph'in konumundan hesaplanır. Bu durumda, GlyphPos yalnızca ilk glyph'in konumunu belirtir.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Glyph konumları dizisini ayarlar EmfPlusPointF nesnelerinin (bölüm 2.2.2.36) bir dizisi, her karakter glyph'inin çıktı konumunu belirtir. GlyphCount öğeleri bulunmalıdır, bu öğeler Glyphs dizisindeki öğelerle bire bir eşleşir. DriverStringOptions bayraklarındaki DriverStringOptionsRealizedAdvance bayrağı ayarlıysa, glyph konumları ilk glyph'in konumundan hesaplanır. Bu durumda, GlyphPos yalnızca ilk glyph'in konumunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Glyph'ler dizisini alır 16 bit değerlerin bir dizisi, çizilecek metin dizesini tanımlar. DriverStringOptionsFlags alanındaki DriverStringOptionsCmapLookup bayrağı ayarlıysa, bu dizideki her değer bir Unicode karakteri belirtir. Aksi takdirde, her değer Flags alanındaki ObjectId değeriyle belirtilen EmfPlusFont nesnesindeki bir karakter glyph'ine indeks belirtir.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Glyph'ler dizisini ayarlar 16 bit değerlerin bir dizisi, çizilecek metin dizesini tanımlar. DriverStringOptionsFlags alanındaki DriverStringOptionsCmapLookup bayrağı ayarlıysa, bu dizideki her değer bir Unicode karakteri belirtir. Aksi takdirde, her değer Flags alanındaki ObjectId değeriyle belirtilen EmfPlusFont nesnesindeki bir karakter glyph'ine indeks belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Bu bit, BrushId alanındaki veri tipini gösterir. Ayarlıysa, BrushId bir EmfPlusARGB nesnesindeki (bölüm 2.2.2.1) renk değerini belirtir. Temizlenmişse, BrushId bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) EMF+ Object Table indeksini içerir.

**Returns:**
boolean - `true` bu örnek renk ise; aksi takdirde, `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Bu örneğin renk olup olmadığını gösteren bir değeri ayarlar. Bu bit, BrushId alanındaki veri tipini gösterir. Ayarlıysa, BrushId bir EmfPlusARGB nesnesindeki (bölüm 2.2.2.1) renk değerini belirtir. Temizlenmişse, BrushId bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) EMF+ Object Table indeksini içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` bu örnek renk ise; aksi takdirde `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


MatrixPresent bayrağını alır. TransformMatrix alanında bir dönüşüm matrisi bulunup bulunmadığını belirten 32 bit işaretsiz tamsayı. 0 - matris yok. 1 - dönüşüm matrisi TransformMatrix alanında bulunur.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


MatrixPresent bayrağını ayarlar. TransformMatrix alanında bir dönüşüm matrisi bulunup bulunmadığını belirten 32 bit işaretsiz tamsayı. 0 - matris yok. 1 - dönüşüm matrisi TransformMatrix alanında bulunur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Dönüşüm matrisini alır. Her bir metin dizisi değerine uygulanacak dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47). Bu verinin varlığı MatrixPresent alanından belirlenir.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Dönüşüm matrisini ayarlar. Her bir metin dizisi değerine uygulanacak dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47). Bu verinin varlığı MatrixPresent alanından belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

