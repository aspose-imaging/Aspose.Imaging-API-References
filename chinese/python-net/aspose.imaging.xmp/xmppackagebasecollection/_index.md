---
title: "XmpPackageBaseCollection 类"
type: docs
weight: 470
url: /zh/python-net/aspose.imaging.xmp/xmppackagebasecollection/
---

**Summary:** Represents collection of [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackageBaseCollection

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection__1) | 初始化 [XmpPackageBaseCollection](/imaging/python-net/aspose.imaging.xmp/xmppackagebasecollection/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| count | int | r | 获取集合中元素的数量。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(package)](#add_package_1) | 添加 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) 的新实例。 |
| clear() | 清除集合中所有 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/)。 |
| [get_package(namespace_uri)](#get_package_namespace_uri_2) | 通过其 namespaceURI 获取 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/)。 |
| [get_packages()](#get_packages__3) | 获取 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) 的数组。 |
| [remove(package)](#remove_package_4) | 移除指定的 XMP 包。 |


### Constructor: XmpPackageBaseCollection() {#XmpPackageBaseCollection__1}


```
 XmpPackageBaseCollection() 
```

初始化 [XmpPackageBaseCollection](/imaging/python-net/aspose.imaging.xmp/xmppackagebasecollection/) 类的新实例。

### Method: add(package) {#add_package_1}


```
 add(package) 
```

添加 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) 的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | 要添加的 XMP 包。 |

### Method: get_package(namespace_uri) {#get_package_namespace_uri_2}


```
 get_package(namespace_uri) 
```

通过其 namespaceURI 获取 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| namespace_uri | string | 用于获取包的命名空间 URI。 |

**Returns**

| Type | Description |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | 返回指定命名空间 Uri 的 XMP 包。 |


### Method: get_packages() {#get_packages__3}


```
 get_packages() 
```

获取 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) 的数组。

**Returns**

| Type | Description |
| :- | :- |
| [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | 返回 XMP 包的数组。 |


### Method: remove(package) {#remove_package_4}


```
 remove(package) 
```

移除指定的 XMP 包。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | 要移除的 XMP 包。 |

