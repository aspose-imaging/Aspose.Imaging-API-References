---
title: Enum EmfPlusStringTrimming
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusStringTrimming enum. The StringTrimming enumeration defines how to trim characters from a string that is too large for the text layout rectangle
type: docs
weight: 5210
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/
---
## EmfPlusStringTrimming enumeration

The StringTrimming enumeration defines how to trim characters from a string that is too large for the text layout rectangle.

```csharp
public enum EmfPlusStringTrimming
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| StringTrimmingNone | `0` | Specifies that no trimming is done. |
| StringTrimmingCharacter | `1` | Specifies that the string is broken at the boundary of the last character that is inside the layout rectangle. This is the default. |
| StringTrimmingWord | `2` | Specifies that the string is broken at the boundary of the last word that is inside the layout rectangle. |
| StringTrimmingEllipsisCharacter | `3` | Specifies that the string is broken at the boundary of the last character that is inside the layout rectangle, and an ellipsis (...) is inserted after the character. |
| StringTrimmingEllipsisWord | `4` | Specifies that the string is broken at the boundary of the last word that is inside the layout rectangle, and an ellipsis (...) is inserted after the word. |
| StringTrimmingEllipsisPath | `5` | Specifies that the center is removed from the string and replaced by an ellipsis. The algorithm keeps as much of the last portion of the string as possible. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


