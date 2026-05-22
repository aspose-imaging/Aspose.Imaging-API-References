---
title: "EmfPlusStringFormat 类"
type: docs
weight: 650
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | 初始化 EmfPlusStringFormat 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | 获取或设置一个 EmfPlusLanguageIdentifier 对象，指定<br/>            字符串中数字使用的语言。<br/>            例如，如果该字符串包含阿拉伯数字，<br/>            此字段必须包含一个语言标识符，<br/>            指定阿拉伯语言 |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | 获取或设置一个 32 位无符号整数，指定如何根据区域设置或语言替换<br/>            字符串中的数字。<br/>            此值必须在 StringDigitSubstitution<br/>            枚举（第 2.1.1.30 节）中定义。 |
| first_tab_offset | float | r/w | 获取或设置一个 32 位浮点值，指定空格的数量<br/>            位于文本行起始处与<br/>            第一个制表位之间 |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | 获取或设置一个 32 位有符号整数，指定类型<br/>            对字符串在键盘<br/>            快捷键前缀（即 & 符号）被遇到时执行的处理。<br/>            基本上，此字段指定是否显示<br/>            与文本相关的键盘快捷键前缀。<br/>            该值必须在 HotkeyPrefix<br/>            枚举（第 2.1.1.14 节）中定义。 |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | 获取或设置一个 EmfPlusLanguageIdentifier 对象（第 2.2.2.23 节）<br/>            指定字符串使用的语言 |
| leading_margin | float | r/w | 获取或设置一个 32 位浮点值，指定要添加到字符串起始位置的空间长度<br/>            默认值为 1/6 英寸；对于排版字体，<br/>            默认值为 0。 |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | 获取或设置一个 32 位无符号整数，指定如何<br/>            在布局矩形中垂直对齐字符串。<br/>            该值必须在 StringAlignment 枚举中定义。 |
| range_count | int | r/w | 获取或设置一个 32 位有符号整数，指定在 StringFormatData 字段中定义的 EmfPlusCharacterRange<br/>            对象（第 2.2.2.8 节）的数量。 |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | 获取或设置一个 32 位无符号整数，指定如何<br/>            在布局矩形中水平对齐字符串。<br/>            该值必须在 StringAlignment<br/>            枚举（第 2.1.1.29 节）中定义。 |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | 获取或设置一个 EmfPlusStringFormatData 对象（第 2.2.2.44 节）<br/>            指定可选的文本布局数据。 |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | 获取或设置一个 32 位无符号整数，指定文本布局<br/>            用于格式化、裁剪和字体处理的选项。<br/>            该值必须由 StringFormat 标志组成<br/>            （第 2.1.2.8 节）。 |
| tabstop_count | int | r/w | 获取或设置一个 32 位有符号整数，指定制表位的数量<br/>            在 StringFormatData 字段中定义的。 |
| tracking | float | r/w | 获取或设置一个 32 位浮点值，指定比例<br/>            水平空间分配给每个字符的<br/>            在指定字符串中相对于字体定义的宽度的<br/>            字符。该属性的较大值表示充足的<br/>            字符之间的空间；小于 1 的值可能导致<br/>            字符重叠。默认值为 1.03；对于排版<br/>            字体，默认值为 1.00。 |
| trailing_margin | float | r/w | 获取或设置一个 32 位浮点值，指定长度<br/>            在字符串后保留的空间。默认值<br/>            为 1/6 英寸；对于排版字体，默认值为 0。 |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | 获取或设置指定如何修剪字符串中<br/>            过大而无法适应布局矩形的字符。此值<br/>            必须在 StringTrimming 枚举（第 2.1.1.31 节）中定义。 |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | 获取或设置版本。 |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

初始化 EmfPlusStringFormat 类的新实例

