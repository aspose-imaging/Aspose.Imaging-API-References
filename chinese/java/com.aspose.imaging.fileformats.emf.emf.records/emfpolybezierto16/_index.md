---
title: "EmfPolyBezierTo16"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_POLYBEZIERTO16 记录根据当前位置信息指定一个或多个贝塞尔曲线。"
type: docs
weight: 88
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo16 extends EmfPolyShape
```

EMR\_POLYBEZIERTO16 记录基于当前位置信息指定一个或多个贝塞尔曲线。

立方贝塞尔曲线使用 aPoints 字段指定的端点和控制点定义。第一条曲线从第一个点绘制到第四个点，使用第二和第三个点作为控制点。序列中的每条后续曲线需要恰好另外三个点：前一条曲线的结束点用作起始点，序列中的接下来的两个点为控制点，第三个点为结束点。立方贝塞尔曲线 SHOULD 使用当前画笔绘制。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPolyBezierTo16(EmfRecord record)](#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPolyBezierTo16` 类的新实例。 |
| [EmfPolyBezierTo16()](#EmfPolyBezierTo16--) | 初始化 `EmfPolyBezierTo16` 类的新实例。 |
### EmfPolyBezierTo16(EmfRecord record) {#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo16(EmfRecord record)
```


初始化 `EmfPolyBezierTo16` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 记录。 |

### EmfPolyBezierTo16() {#EmfPolyBezierTo16--}
```
public EmfPolyBezierTo16()
```


初始化 `EmfPolyBezierTo16` 类的新实例。

