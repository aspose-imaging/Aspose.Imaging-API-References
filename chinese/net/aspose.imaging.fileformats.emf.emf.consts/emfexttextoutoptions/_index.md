---
title: "枚举 EmfExtTextOutOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfExtTextOutOptions 枚举。ExtTextOutOptions 枚举指定控制 EMR_SMALLTEXTOUT 第 2.3.5.37 节记录和 EmrText 对象中文本输出各方面的参数。"
type: docs
weight: 2720
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
## EmfExtTextOutOptions enumeration

该 ExtTextOutOptions 枚举指定了控制 EMR_SMALLTEXTOUT（第 2.3.5.37 节）记录和 EmrText 对象中文本输出各方面的参数。

```csharp
[Flags]
public enum EmfExtTextOutOptions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ETO_OPAQUE | `2` | 此位指示应使用当前背景颜色填充矩形。 |
| ETO_CLIPPED | `4` | 此位指示应将文本裁剪到矩形内。 |
| ETO_GLYPH_INDEX | `10` | 此位指示输出文本字符串中字符的代码实际上是 TrueType 字体中字符字形的索引。字形索引是特定于字体的，因此在回放时显示正确字符，需要使用的字体必须与生成索引时使用的字体完全相同。 |
| ETO_RTLREADING | `80` | 此位指示文本必须按从右到左的阅读顺序布局，而不是默认的从左到右顺序。仅当在回放设备上下文中选择的字体为希伯来语或阿拉伯语时才应应用此设置。 |
| ETO_NO_RECT | `100` | 此位指示记录未为文本输出指定边界矩形。 |
| ETO_SMALL_CHARS | `200` | 此位指示输出文本字符串中字符的代码为 8 位，来源于 16 位 Unicode UTF16-LE 字符代码的低字节，其中高字节假定为 0。 |
| ETO_NUMERICSLOCAL | `400` | 此位指示显示数字时应使用符合地区设置的数字字符。 |
| ETO_NUMERICSLATIN | `800` | 此位指示显示数字时应使用欧洲数字。 |
| ETO_IGNORELANGUAGE | `1000` | 此位指示不应对从右到左的字符串进行特殊的操作系统字形放置处理；也就是说，所有字形定位应由元文件中的绘图和状态记录负责。 |
| ETO_PDY | `2000` | 此位指示应提供水平和垂直字符位移值。 |
| ETO_REVERSE_INDEX_MAP | `10000` | 此位已保留，不应使用。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


