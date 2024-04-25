---
title: EmfPlusStringTrimming
second_title: Aspose.Imaging for Java API Reference
description: The StringTrimming enumeration defines how to trim characters from a string that is too large for the text layout rectangle.
type: docs
weight: 51
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringTrimming extends System.Enum
```

The StringTrimming enumeration defines how to trim characters from a string that is too large for the text layout rectangle.
## Fields

| Field | Description |
| --- | --- |
| [StringTrimmingNone](#StringTrimmingNone) | Specifies that no trimming is done. |
| [StringTrimmingCharacter](#StringTrimmingCharacter) | Specifies that the string is broken at the boundary of the last character that is inside the layout rectangle. |
| [StringTrimmingWord](#StringTrimmingWord) | Specifies that the string is broken at the boundary of the last word that is inside the layout rectangle. |
| [StringTrimmingEllipsisCharacter](#StringTrimmingEllipsisCharacter) | Specifies that the string is broken at the boundary of the last character that is inside the layout rectangle, and an ellipsis (...) is inserted after the character. |
| [StringTrimmingEllipsisWord](#StringTrimmingEllipsisWord) | Specifies that the string is broken at the boundary of the last word that is inside the layout rectangle, and an ellipsis (...) is inserted after the word. |
| [StringTrimmingEllipsisPath](#StringTrimmingEllipsisPath) | Specifies that the center is removed from the string and replaced by an ellipsis. |
### StringTrimmingNone {#StringTrimmingNone}
```
public static final int StringTrimmingNone
```


Specifies that no trimming is done.

### StringTrimmingCharacter {#StringTrimmingCharacter}
```
public static final int StringTrimmingCharacter
```


Specifies that the string is broken at the boundary of the last character that is inside the layout rectangle. This is the default.

### StringTrimmingWord {#StringTrimmingWord}
```
public static final int StringTrimmingWord
```


Specifies that the string is broken at the boundary of the last word that is inside the layout rectangle.

### StringTrimmingEllipsisCharacter {#StringTrimmingEllipsisCharacter}
```
public static final int StringTrimmingEllipsisCharacter
```


Specifies that the string is broken at the boundary of the last character that is inside the layout rectangle, and an ellipsis (...) is inserted after the character.

### StringTrimmingEllipsisWord {#StringTrimmingEllipsisWord}
```
public static final int StringTrimmingEllipsisWord
```


Specifies that the string is broken at the boundary of the last word that is inside the layout rectangle, and an ellipsis (...) is inserted after the word.

### StringTrimmingEllipsisPath {#StringTrimmingEllipsisPath}
```
public static final int StringTrimmingEllipsisPath
```


Specifies that the center is removed from the string and replaced by an ellipsis. The algorithm keeps as much of the last portion of the string as possible.

