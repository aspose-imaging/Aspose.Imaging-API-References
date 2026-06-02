---
title: "XmpPacketWrapper 类"
type: docs
weight: 480
url: /zh/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | 初始化 [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) 类的新实例。 |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | 初始化 [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | 获取头部处理指令。 |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | 获取 XMP 元数据。可选。 |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | 获取 XMP 中的 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) 数组。 |
| packages_count | int | r | 获取 XMP 结构中包的数量。 |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | 获取尾部处理指令。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | 添加该包。 |
| clear_packages() | 移除 XMP 中的所有 [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/)。 |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | 确定包是否存在于 XMP 包装器中。 |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | 通过命名空间 URI 获取包。 |
| [get_xml_value()](#get_xml_value__4) | 将 XMP 值转换为 XML 表示。 |
| [remove_package(package)](#remove_package_package_5) | 移除 XMP 包。 |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

初始化 [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) 类的新实例。

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

初始化 [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | 处理指令的 XMP 标头。 |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | 处理指令的 XMP 尾部。 |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | XMP 元数据。 |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

添加该包。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | 该包。 |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

确定包是否存在于 XMP 包装器中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| namespace_uri | string | 包的模式 URI。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果在 XMP 包装器中存在具有指定命名空间 URI 的包，则返回 true。 |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

通过命名空间 URI 获取包。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| namespace_uri | string | 包的模式 URI。 |

**Returns**

| Type | Description |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | 返回指定命名空间 URI 的 XMP 包。 |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回转换为 XML 的 XMP 值。 |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

移除 XMP 包。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | 该包。 |

