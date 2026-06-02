---
title: "XmpPackage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP paketi için temel soyutlamayı temsil eder."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

XMP paketi için temel soyutlamayı temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Yeni bir `XmpPackage` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | XML ad alanını alır. |
| [getPrefix()](#getPrefix--) | Öneki alır. |
| [getNamespaceUri()](#getNamespaceUri--) | Ad alanı URI'sini alır. |
| [getKeys()](#getKeys--) | XMP paketindeki anahtarları alır. |
| [getCount()](#getCount--) | XMP anahtar sayısını alır. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Bu koleksiyonun belirtilen anahtarı içerip içermediğini belirler. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Belirtilen anahtara sahip `Object`'i alır veya ayarlar. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen anahtara sahip `Object`'i ayarlar. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Değeri belirtilen anahtara ekler. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Değeri belirtilen anahtara ekler. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | `key` ile değeri alır. |
| [remove(String key)](#remove-java.lang.String-) | Belirtilen anahtara sahip değeri kaldırır. |
| [clear()](#clear--) | Bu örneği temizler. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | değeri ayarlar. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | değeri ayarlar. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | XMP tip değerini ayarlar. |
| [getXmlValue()](#getXmlValue--) | XMP değerini XML temsiline dönüştürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Yeni bir `XmpPackage` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| önek | java.lang.String | Önek. |
| namespaceUri | java.lang.String | Ad alanı URI'si. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


XML ad alanını alır.

Değer: XML ad alanı.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Öneki alır.

Değer: Önek.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ad alanı URI'sini alır.

Değer: Ad alanı URI'si.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


XMP paketindeki anahtarları alır.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


XMP anahtar sayısını alır.

**Returns:**
int - XMP anahtar sayısı.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Bu koleksiyonun belirtilen anahtarı içerip içermediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Kontrol edilecek anahtar. |

**Returns:**
boolean - koleksiyon belirtilen anahtarı içeriyorsa `true`; aksi takdirde `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Belirtilen anahtara sahip `Object`'i alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Değeri tanımlayan anahtar. |

**Returns:**
java.lang.Object - belirtilen anahtara sahip `Object` döndürür.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Belirtilen anahtara sahip `Object`'i ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Değeri tanımlayan anahtar. |
| değer | java.lang.Object | `Object` değeri. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Değeri belirtilen anahtara ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | java.lang.String | Eklenecek değer. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Değeri belirtilen anahtara ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | java.lang.Object | Eklenecek değer. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


`key` ile değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | XMP öğe anahtarı. |
| değer | java.lang.Object[] | XMP değeri. |

**Returns:**
boolean - koleksiyon `key` anahtarını içeriyorsa `true`; aksi takdirde `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Belirtilen anahtara sahip değeri kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Kaldırılan değer ile tanımlanan anahtarın dize temsili. |

**Returns:**
boolean - belirtilen anahtara sahip değer kaldırıldıysa true döndürür.
### clear() {#clear--}
```
public void clear()
```


Bu örneği temizler.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | Eklenecek değer. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Eklenecek değer. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


XMP tip değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Ayarlanan değer ile tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | Ayarlanacak değer. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML temsiline dönüştürülmüş olarak döndürür.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir `T:System.Collections.Generic.IEnumerator\`1`.
