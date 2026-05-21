---
title: "XmpCollection"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir XMP öğe koleksiyonu."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

Bir XMP öğe koleksiyonu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Yeni öğe ekler. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Bir XMP veri öğesi ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki öğeyi kaldırır. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Koleksiyona bir öğe ekler. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Koleksiyonun öğelerini belirli bir dizi indeksinden başlayarak bir diziye kopyalar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Bunun XMP dize değerini alır. |
| [getXmlValue()](#getXmlValue--) | XMP değerini XML temsiline dönüştürür. |
| [toString()](#toString--) | Bu örneği temsil eden bir XML dizesi döndürür. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


[XmpCollection](../../com.aspose.imaging.xmp/xmpcollection) sınıfının yeni bir örneğini başlatır.

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Yeni öğe ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| öğe | java.lang.Object | Listeye eklenecek öğe. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Bir XMP veri öğesi ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| öğe | java.lang.Object | Bir XMP öğesi. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen indeksteki öğeyi kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Koleksiyona bir öğe ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Koleksiyona eklenecek nesne. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Koleksiyonun öğelerini belirli bir dizi indeksinden başlayarak bir diziye kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | Koleksiyondan kopyalanan öğelerin hedefi olan tek boyutlu dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başladığı dizideki sıfır tabanlı indeks. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Bunun XMP dize değerini alır.

**Returns:**
java.lang.String - XMP biçiminde içerilen dize değerini döndürür.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML temsiline dönüştürülmüş olarak döndürür.
### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir XML dizesi döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir XML String.
