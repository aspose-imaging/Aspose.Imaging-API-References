---
title: "EmfPlusDrawString"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusDrawString kaydı dize biçimlendirmeli metin çıktısını belirtir"
type: docs
weight: 28
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

EmfPlusDrawString kaydı dize biçimlendirmeli metin çıktısını belirtir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | `EmfPlusDrawString` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isColor()](#isColor--) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setColor(boolean value)](#setColor-boolean-) | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getObjectId()](#getObjectId--) | Nesne tanımlayıcısını alır veya ayarlar. |
| [setObjectId(byte value)](#setObjectId-byte-) | Nesne tanımlayıcısını alır veya ayarlar. |
| [getBrushId()](#getBrushId--) | Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz tamsayı; içeriği Flags alanındaki S biti tarafından belirlenir. |
| [setBrushId(int value)](#setBrushId-int-) | Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz tamsayı; içeriği Flags alanındaki S biti tarafından belirlenir. |
| [getFormatId()](#getFormatId--) | Biçim tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda isteğe bağlı bir EmfPlusStringFormat nesnesinin (bölüm 2.2.1.9) dizinini belirten 32 bit işaretsiz tamsayı. |
| [setFormatId(int value)](#setFormatId-int-) | Biçim tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda isteğe bağlı bir EmfPlusStringFormat nesnesinin (bölüm 2.2.1.9) dizinini belirten 32 bit işaretsiz tamsayı. |
| [getLength()](#getLength--) | Dizideki karakter sayısını belirten uzunluk 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setLength(int value)](#setLength-int-) | Dizideki karakter sayısını belirten uzunluk 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getLayoutRect()](#getLayoutRect--) | Diziyi alacak hedefin sınırlayıcı alanını tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) olan yerleşim dikdörtgenini alır veya ayarlar. |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Diziyi alacak hedefin sınırlayıcı alanını tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) olan yerleşim dikdörtgenini alır veya ayarlar. |
| [getStringData()](#getStringData--) | Çizilecek dizeyi belirten 16 bit Unicode karakterlerden oluşan bir dizi olan dize verisini alır veya ayarlar. |
| [setStringData(String value)](#setStringData-java.lang.String-) | Çizilecek dizeyi belirten 16 bit Unicode karakterlerden oluşan bir dizi olan dize verisini alır veya ayarlar. |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


`EmfPlusDrawString` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Kaynak. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Nesne tanımlayıcısını alır veya ayarlar. Metni işlemek için EMF+ Nesne Tablosundaki bir EmfPlusFont nesnesinin (bölüm 2.2.1.3) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Nesne tanımlayıcısını alır veya ayarlar. Metni işlemek için EMF+ Nesne Tablosundaki bir EmfPlusFont nesnesinin (bölüm 2.2.1.3) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır.

Değer: Nesne tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz tamsayı; içeriği Flags alanındaki S biti tarafından belirlenir. Bu tanım, ön plan metin rengini boyamak için kullanılır; yani yalnızca glifler kendileri.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Fırça tanımlayıcısını alır veya ayarlar. Fırçayı belirten 32 bit işaretsiz tamsayı; içeriği Flags alanındaki S biti tarafından belirlenir. Bu tanım, ön plan metin rengini boyamak için kullanılır; yani yalnızca glifler kendileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Biçim tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda isteğe bağlı bir EmfPlusStringFormat nesnesinin (bölüm 2.2.1.9) dizinini belirten 32 bit işaretsiz tamsayı. Bu nesne, bir dizeye uygulanacak metin yerleşim bilgilerini ve görüntü manipülasyonlarını belirtir.

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Biçim tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda isteğe bağlı bir EmfPlusStringFormat nesnesinin (bölüm 2.2.1.9) dizinini belirten 32 bit işaretsiz tamsayı. Bu nesne, bir dizeye uygulanacak metin yerleşim bilgilerini ve görüntü manipülasyonlarını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Dizideki karakter sayısını belirten uzunluk 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Dizideki karakter sayısını belirten uzunluk 32 bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Diziyi alacak hedefin sınırlayıcı alanını tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) olan yerleşim dikdörtgenini alır veya ayarlar.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Diziyi alacak hedefin sınırlayıcı alanını tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) olan yerleşim dikdörtgenini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Çizilecek dizeyi belirten 16 bit Unicode karakterlerden oluşan bir dizi olan dize verisini alır veya ayarlar.

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Çizilecek dizeyi belirten 16 bit Unicode karakterlerden oluşan bir dizi olan dize verisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

