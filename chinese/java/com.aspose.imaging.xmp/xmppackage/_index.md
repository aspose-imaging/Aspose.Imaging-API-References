---
title: "XmpPackage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 XMP 包的基础抽象。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

表示 XMP 包的基础抽象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | 初始化 `XmpPackage` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | 获取 XML 命名空间。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取命名空间 URI。 |
| [getKeys()](#getKeys--) | 获取 XMP 包中的键。 |
| [getCount()](#getCount--) | 获取 XMP 键的计数。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 确定此集合是否具有指定键。 |
| [get_Item(String key)](#get-Item-java.lang.String-) | 获取或设置具有指定键的 `Object`。 |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 设置具有指定键的 `Object`。 |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | 向指定键添加值。 |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | 向指定键添加值。 |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | 通过 `key` 获取值。 |
| [remove(String key)](#remove-java.lang.String-) | 移除具有指定键的值。 |
| [clear()](#clear--) | 清除此实例。 |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | 设置值。 |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | 设置值。 |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | 设置 XMP 类型值。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示形式。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


初始化 `XmpPackage` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |
| namespaceUri | java.lang.String | 命名空间 URI。 |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


获取 XML 命名空间。

值：XML 命名空间。

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

值：前缀。

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取命名空间 URI。

值：命名空间 URI。

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


获取 XMP 包中的键。

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


获取 XMP 键的计数。

**Returns:**
int - XMP 键计数。
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


确定此集合是否具有指定键。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 要检查的键。 |

**Returns:**
boolean - 如果集合包含指定键则为 `true`；否则为 `false`。
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


获取或设置具有指定键的 `Object`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 标识值的键。 |

**Returns:**
java.lang.Object - 返回具有指定键的 `Object`。
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


设置具有指定键的 `Object`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 标识值的键。 |
| value | java.lang.Object | `Object` 值。 |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


向指定键添加值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 键的字符串表示形式，用于标识添加的值。 |
| value | java.lang.String | 要添加到的值。 |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


向指定键添加值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 键的字符串表示形式，用于标识添加的值。 |
| value | java.lang.Object | 要添加到的值。 |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


通过 `key` 获取值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | XMP 元素键。 |
| value | java.lang.Object[] | XMP 值。 |

**Returns:**
boolean - 如果集合包含 `key` 则为 `true`；否则为 `false`。
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


移除具有指定键的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 已删除值对应的键的字符串表示。 |

**Returns:**
boolean - 如果已删除具有指定键的值则返回 true。
### clear() {#clear--}
```
public void clear()
```


清除此实例。

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


设置值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 键的字符串表示形式，用于标识添加的值。 |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | 要添加到的值。 |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


设置值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 键的字符串表示形式，用于标识添加的值。 |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | 要添加到的值。 |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


设置 XMP 类型值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 已设置值对应的键的字符串表示。 |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | 要设置的值。 |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 XMP 值转换为 XML 表示形式。

**Returns:**
java.lang.String - 返回转换为 XML 表示形式的 XMP 值。
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


返回遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - 可用于遍历集合的 `T:System.Collections.Generic.IEnumerator\`1`。
