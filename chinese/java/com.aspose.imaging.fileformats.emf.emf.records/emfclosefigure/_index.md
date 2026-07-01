---
title: "EmfCloseFigure"
second_title: "Aspose.Imaging for Java API 参考"
description: "此记录关闭路径中的打开图形。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

此记录关闭路径中的一个打开的图形。处理 EMR\_CLOSEFIGURE 记录时，必须通过从当前位点绘制一条线到图形的第一个点来关闭图形，然后必须使用线段连接样式连接这些线段。如果使用 EMR\_LINETO 记录而不是 EMR\_CLOSEFIGURE 记录来关闭图形，则使用端帽来创建拐角而不是连接。EMR\_LINETO 在第 2.3.5.13 节中指定。只有在回放设备上下文中存在打开的路径括号时，才应使用 EMR\_CLOSEFIGURE 记录。路径中的图形在未通过处理此记录显式关闭之前都是打开的。

注意：即使当前点与图形的起始点相同，图形仍可能是打开的。处理 EMR\_CLOSEFIGURE 记录后，向路径添加线段或曲线必须启动一个新图形。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | 初始化 `EmfCloseFigure` 类的新实例。 |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


初始化 `EmfCloseFigure` 类的新实例。

