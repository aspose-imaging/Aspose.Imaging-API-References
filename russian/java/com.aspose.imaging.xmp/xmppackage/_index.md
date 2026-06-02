---
title: "XmpPackage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет базовую абстракцию для пакета XMP."
type: docs
weight: 19
url: /ru/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Представляет базовую абстракцию для пакета XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса `XmpPackage`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Получает XML‑пространство имён. |
| [getPrefix()](#getPrefix--) | Получает префикс. |
| [getNamespaceUri()](#getNamespaceUri--) | Получает URI пространства имён. |
| [getKeys()](#getKeys--) | Получает ключи в XMP‑пакете. |
| [getCount()](#getCount--) | Получает количество ключей XMP. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Определяет, содержит ли эта коллекция указанный ключ. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Получает или задаёт `Object` с указанным ключом. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Задаёт `Object` с указанным ключом. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Добавляет значение к указанному ключу. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Добавляет значение к указанному ключу. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Получает значение по `key`. |
| [remove(String key)](#remove-java.lang.String-) | Удаляет значение с указанным ключом. |
| [clear()](#clear--) | Очищает этот экземпляр. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Устанавливает значение. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | Устанавливает значение. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Задаёт значение типа XMP. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в XML-представление. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Инициализирует новый экземпляр класса `XmpPackage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | java.lang.String | Префикс. |
| namespaceUri | java.lang.String | URI пространства имён. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Получает XML‑пространство имён.

Значение: XML‑пространство имён.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Получает префикс.

Значение: префикс.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Получает URI пространства имён.

Значение: URI пространства имён.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Получает ключи в XMP‑пакете.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


Получает количество ключей XMP.

**Returns:**
int - количество ключей XMP.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Определяет, содержит ли эта коллекция указанный ключ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ, который нужно проверить. |

**Returns:**
boolean - `true`, если коллекция содержит указанный ключ; иначе `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Получает или задаёт `Object` с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ, идентифицирующий значение. |

**Returns:**
java.lang.Object - Возвращает `Object` с указанным ключом.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Задаёт `Object` с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ, идентифицирующий значение. |
| value | java.lang.Object | Значение `Object`. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Добавляет значение к указанному ключу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Строковое представление ключа, идентифицированного добавленным значением. |
| value | java.lang.String | Значение, к которому добавлять. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Добавляет значение к указанному ключу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Строковое представление ключа, идентифицированного добавленным значением. |
| value | java.lang.Object | Значение, к которому добавлять. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


Получает значение по `key`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ элемента XMP. |
| value | java.lang.Object[] | Значение XMP. |

**Returns:**
boolean - `true`, если коллекция содержит `key`; иначе `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Удаляет значение с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Строковое представление ключа, связанного с удалённым значением. |

**Returns:**
boolean - Возвращает true, если значение с указанным ключом было удалено.
### clear() {#clear--}
```
public void clear()
```


Очищает этот экземпляр.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Устанавливает значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Строковое представление ключа, идентифицированного добавленным значением. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | Значение, к которому добавлять. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


Устанавливает значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Строковое представление ключа, идентифицированного добавленным значением. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Значение, к которому добавлять. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Задаёт значение типа XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Строковое представление ключа, связанного с установленным значением. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | Значение, которое следует установить. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение XMP в XML-представление.

**Returns:**
java.lang.String — Возвращает значение XMP, преобразованное в XML-представление.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Возвращает перечислитель, который проходит по коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - `T:System.Collections.Generic.IEnumerator\\`1`, который можно использовать для перебора элементов коллекции.
