---
title: "XmpPackageBaseCollection"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 XmpPackage 的集合。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

表示 `XmpPackage` 的集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | 初始化 `XmpPackageBaseCollection` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取集合中元素的数量。 |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | 添加 `XmpPackage` 的新实例。 |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | 移除指定的 XMP 包。 |
| [getPackages()](#getPackages--) | 获取 `XmpPackage` 的数组。 |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | 通过其 namespaceURI 获取 `XmpPackage`。 |
| [clear()](#clear--) | 清除集合中的所有 `XmpPackage`。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


初始化 `XmpPackageBaseCollection` 类的新实例。

### getCount() {#getCount--}
```
public int getCount()
```


获取集合中元素的数量。

值：集合中元素的数量。

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


添加 `XmpPackage` 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | 要添加的 XMP 包\_。 |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


移除指定的 XMP 包。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | 要删除的 XMP 包\_。 |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


获取 `XmpPackage` 的数组。

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - 返回 XMP 包的数组。
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


通过其 namespaceURI 获取 `XmpPackage`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 获取 package\_ 的命名空间 URI。 |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


清除集合中的所有 `XmpPackage`。

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


返回一个遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - 一个可用于遍历集合的 `System.Collections.IEnumerator` 对象。
