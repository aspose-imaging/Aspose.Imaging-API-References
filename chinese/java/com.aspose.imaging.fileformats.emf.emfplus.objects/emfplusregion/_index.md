---
title: "EmfPlusRegion"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusRegion 对象指定定义非直线形状的线段和曲线段。"
type: docs
weight: 68
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

EmfPlusRegion 对象指定定义非直线形状的线段和曲线段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | 获取或设置一个包含 RegionNodeCount+1 个 EmfPlusRegionNode 对象的数组（第 2.2.2.40 节）。 |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | 获取或设置一个包含 RegionNodeCount+1 个 EmfPlusRegionNode 对象的数组（第 2.2.2.40 节）。 |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


获取或设置一个包含 RegionNodeCount+1 个 EmfPlusRegionNode 对象的数组（第 2.2.2.40 节）。区域被指定为区域节点的二叉树，每个节点必须是终端节点或指定一个或两个子节点。RegionNode 必须至少包含一个元素。

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


获取或设置一个包含 RegionNodeCount+1 个 EmfPlusRegionNode 对象的数组（第 2.2.2.40 节）。区域被指定为区域节点的二叉树，每个节点必须是终端节点或指定一个或两个子节点。RegionNode 必须至少包含一个元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

