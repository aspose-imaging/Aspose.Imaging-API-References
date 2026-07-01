---
title: "ComplexTypeBase"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 XMP 复合值类型的基础抽象。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.types.complex/complextypebase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public class ComplexTypeBase extends XmpTypeBase
```

表示 XMP 复合值类型的基础抽象。

查看更多：XMP Specification Part 2, Chapter 1.2.2
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ComplexTypeBase(String prefix, String namespaceUri)](#ComplexTypeBase-java.lang.String-java.lang.String-) | 初始化 `ComplexTypeBase` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取默认命名空间 URI。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### ComplexTypeBase(String prefix, String namespaceUri) {#ComplexTypeBase-java.lang.String-java.lang.String-}
```
public ComplexTypeBase(String prefix, String namespaceUri)
```


初始化 `ComplexTypeBase` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |
| namespaceUri | java.lang.String | 命名空间 URI。 |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

**Returns:**
java.lang.String - 前缀。
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取默认命名空间 URI。

**Returns:**
java.lang.String - 默认命名空间 URI。
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
