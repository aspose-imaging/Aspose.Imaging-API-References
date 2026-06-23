---
title: "EmfPlusRegionNode"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EmfPlusRegionNode 对象指定图形区域的节点。"
type: docs
weight: 69
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

该 EmfPlusRegionNode 对象指定图形区域的节点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | 获取或设置可选的、可变长度数据，用于定义 Type 字段中指定的区域节点数据对象。 |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | 获取或设置可选的、可变长度数据，用于定义 Type 字段中指定的区域节点数据对象。 |
| [getType()](#getType--) | 获取或设置 32 位无符号整数，指定 RegionNodeData 字段中的数据类型。 |
| [setType(int value)](#setType-int-) | 获取或设置 32 位无符号整数，指定 RegionNodeData 字段中的数据类型。 |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


获取或设置可选的、可变长度数据，用于定义 Type 字段中指定的区域节点数据对象。该数据的内容和格式可能因不同的区域节点类型而异。如果节点类型为 RegionNodeDataTypeEmpty 或 RegionNodeDataTypeInfinite，则此字段 MUST NOT 出现。此对象是通用的，用于指定不同类型的区域节点数据，包括：一个 EmfPlusRegionNodePath 对象（第 2.2.2.42 节），用于终端节点；一个 EmfPlusRectF 对象（第 2.2.2.39 节），用于终端节点；以及一个 EmfPlusRegionNodeChildNodes 对象（第 2.2.2.41 节），用于非终端节点。

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


获取或设置可选的、可变长度数据，用于定义 Type 字段中指定的区域节点数据对象。该数据的内容和格式可能因不同的区域节点类型而异。如果节点类型为 RegionNodeDataTypeEmpty 或 RegionNodeDataTypeInfinite，则此字段 MUST NOT 出现。此对象是通用的，用于指定不同类型的区域节点数据，包括：一个 EmfPlusRegionNodePath 对象（第 2.2.2.42 节），用于终端节点；一个 EmfPlusRectF 对象（第 2.2.2.39 节），用于终端节点；以及一个 EmfPlusRegionNodeChildNodes 对象（第 2.2.2.41 节），用于非终端节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


获取或设置 32 位无符号整数，指定 RegionNodeData 字段中的数据类型。此值 MUST 在 RegionNodeDataType 枚举（第 2.1.1.27 节）中定义。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取或设置 32 位无符号整数，指定 RegionNodeData 字段中的数据类型。此值 MUST 在 RegionNodeDataType 枚举（第 2.1.1.27 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

