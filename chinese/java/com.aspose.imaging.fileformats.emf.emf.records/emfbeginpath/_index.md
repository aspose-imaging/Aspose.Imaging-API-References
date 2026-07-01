---
title: "EmfBeginPath"
second_title: "Aspose.Imaging for Java API 参考"
description: "此记录在当前回放设备上下文中打开路径括号。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

此记录在当前回放设备上下文中打开一个路径括号。路径括号打开后，应用程序可以开始处理记录以定义路径中的点。应用程序必须通过处理 EMR\\_ENDPATH 记录来关闭打开的路径括号。当应用程序处理 EMR\\_BEGINPATH 记录时，必须从回放设备上下文中丢弃所有先前的路径。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | 初始化 `EmfBeginPath` 类的新实例。 |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


初始化 `EmfBeginPath` 类的新实例。

