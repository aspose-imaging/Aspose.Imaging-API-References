---
title: "EmfPlusMetafile.MetafileData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusMetafile 属性。获取或设置指定嵌入元文件的可变长度数据。该数据的内容和格式可能因每种元文件类型而异。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/metafiledata/
---
## EmfPlusMetafile.MetafileData property

获取或设置可变长度数据，以指定嵌入的元文件。数据的内容和格式可能因元文件类型而异。

```csharp
public byte[] MetafileData { get; set; }
```

## 备注

图形图像由 EmfPlusImage 对象（第 2.2.1.4 节）指定。如果在其 Type 字段中指定了 ImageTypeMetafile，则 EmfPlusImage 对象的 ImageData 字段中必须存在 EmfPlusMetafile 对象。此对象是通用的，用于不同类型的数据，包括：WMF 元文件 [MS-WMF]；可放置的 WMF 元文件；EMF 元文件 [MS-EMF]；仅使用 EMF+ 记录指定图形操作的 EMF+ 元文件；以及同时使用 EMF+ 和 EMF 记录指定图形操作的 EMF+ 元文件。有关其他结构对象的规范，请参见第 2.2.2 节。

### 另请参见

* class [EmfPlusMetafile](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusmetafile/)
* assembly [Aspose.Imaging](../../../)


