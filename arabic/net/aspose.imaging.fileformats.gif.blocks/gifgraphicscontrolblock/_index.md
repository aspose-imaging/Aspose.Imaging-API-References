---
title: "الفئة GifGraphicsControlBlock"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Gif.Blocks.GifGraphicsControlBlock. كتلة تحكم رسومات GIF."
type: docs
weight: 6740
url: /ar/net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
## GifGraphicsControlBlock class

كتلة التحكم الرسومي لـ Gif.

```csharp
public class GifGraphicsControlBlock : GifBlock
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor)() | يُنشئ مثلاً جديداً من الفئة `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor_1)(byte, ushort, byte) | يُنشئ مثلاً جديداً من الفئة `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor_2)(ushort, bool, byte, bool, DisposalMethod) | يُنشئ مثلاً جديداً من الفئة `GifGraphicsControlBlock`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DelayTime](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/delaytime/) { get; set; } | الحصول أو تعيين زمن تأخير الإطار معبرًا عنه بـ 1/100 ثانية. |
| [DisposalMethod](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/disposalmethod/) { get; set; } | يحصل أو يعيّن طريقة التخلص. |
| [Flags](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/flags/) { get; set; } | يحصل أو يعيّن العلامات. |
| [HasTransparentColor](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/hastransparentcolor/) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كانت كتلة تحكم الرسومات تحتوي على لون شفاف. |
| [IsChanged](../../aspose.imaging.fileformats.gif/gifblock/ischanged/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الكتلة قد تغيرت وتحتاج إلى حفظ. |
| [TransparentColorIndex](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/transparentcolorindex/) { get; set; } | الحصول أو تعيين فهرس اللون الشفاف. |
| [UserInputExpected](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/userinputexpected/) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كان من المتوقع إدخال المستخدم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/save/)(Stream) | يحفظ الكتلة إلى الدفق المحدد. |
| static [CreateFlags](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/createflags/)(bool, bool, DisposalMethod) | ينشئ العلامات. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [BlockHeaderSize](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/blockheadersize/) | يحدد حجم رأس الكتلة. |
| const [ExtensionLabel](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/extensionlabel/) | تسمية الامتداد. |
| const [SubBlockSize](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/subblocksize/) | الحصول على حجم الكتلة الفرعية. |

### انظر أيضًا

* class [GifBlock](../../aspose.imaging.fileformats.gif/gifblock/)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../aspose.imaging.fileformats.gif.blocks/)
* assembly [Aspose.Imaging](../../)


