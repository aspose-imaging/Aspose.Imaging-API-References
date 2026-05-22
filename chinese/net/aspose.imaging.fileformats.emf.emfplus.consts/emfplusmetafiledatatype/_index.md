---
title: "枚举 EmfPlusMetafileDataType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusMetafileDataType 枚举。MetafileDataType 枚举定义了可以嵌入 EMF 元文件中的元文件数据类型。"
type: docs
weight: 5040
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusmetafiledatatype/
---
## EmfPlusMetafileDataType enumeration

MetafileDataType 枚举定义了可以嵌入 EMF+ 元文件中的元文件数据类型。

```csharp
public enum EmfPlusMetafileDataType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| MetafileDataTypeWmf | `1` | 指定该元文件是 WMF 元文件，使用 WMF 记录指定图形操作，如 [MS-WMF] 所述。 |
| MetafileDataTypeWmfPlaceable | `2` | 指定该元文件是 WMF 元文件，使用 WMF 记录指定图形操作，并包含额外的头信息，使 WMF 元文件与设备无关，如 [MS-WMF] 所述。 |
| MetafileDataTypeEmf | `3` | 指定该元文件是 EMF 元文件，使用 EMF 记录指定图形操作，如 [MS-EMF] 所述。 |
| MetafileDataTypeEmfPlusOnly | `4` | 指定该元文件是 EMF+ 元文件，仅使用 EMF+ 记录指定图形操作。 |
| MetafileDataTypeEmfPlusDual | `5` | 指定该元文件是 EMF+ 元文件，使用 EMF 和 EMF+ 记录共同指定图形操作。 |

## 备注

嵌入的元文件数据由 EmfPlusMetafileData 对象（第 2.2.2.27 节）指定。

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


