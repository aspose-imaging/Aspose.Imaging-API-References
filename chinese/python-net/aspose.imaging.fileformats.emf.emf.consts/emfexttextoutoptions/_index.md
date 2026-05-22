---
title: "EmfExtTextOutOptions 枚举"
type: docs
weight: 100
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---

ExtTextOutOptions 枚举指定了控制文本输出各方面的参数，<br/>            通过 EMR_SMALLTEXTOUT（第 2.3.5.37 节）记录和 EmrText 对象实现。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfExtTextOutOptions

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| ETO_CLIPPED | 此位指示文本应被裁剪到矩形。 |
| ETO_GLYPH_INDEX | 此位指示输出文本字符串中字符的代码实际上是<br/>TrueType 字体中字符字形的索引。字形索引是特定于字体的，<br/>因此要在回放时显示正确的字符，所使用的字体必须<br/>与生成索引时使用的字体完全相同。 |
| ETO_IGNORELANGUAGE | 此位指示对于从右到左的字符串，不应对字形放置进行任何特殊的操作系统处理；也就是说，所有字形定位应由<br/>元文件中的绘制和状态记录来处理。 |
| ETO_NO_RECT | 此位指示记录未为文本输出指定边界矩形。 |
| ETO_NUMERICSLATIN | 此位指示显示数字时应使用欧洲数字。 |
| ETO_NUMERICSLOCAL | 此位指示显示数字时应使用符合本地语言的数字。 |
| ETO_OPAQUE | 此位指示应使用当前背景颜色来填充矩形。 |
| ETO_PDY | 此位指示应提供水平和垂直字符位移值。 |
| ETO_REVERSE_INDEX_MAP | 此位已保留，且不应使用 |
| ETO_RTLREADING | 此位指示文本必须按从右到左的阅读顺序布局，<br/>            而不是默认的从左到右顺序。仅当在回放设备上下文中选择的字体是希伯来语或阿拉伯语时，才应使用此位。 |
| ETO_SMALL_CHARS | 此位指示输出文本字符串中字符的代码为 8 位，<br/>            来源于 16 位 Unicode UTF16-LE 字符代码的低字节，<br/>            其中高字节假定为 0。 |
