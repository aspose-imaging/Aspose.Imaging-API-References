---
title: MagicWandSettings.ColorComparison
second_title: Aspose.Imaging for Java API Reference
description: Delegate for  comparison with a defined threshold.
type: docs
weight: 10
url: /com.aspose.imaging.magicwand/magicwandsettings.colorcomparison/
---```
public static interface MagicWandSettings.ColorComparison
```

Delegate for [Color](../../com.aspose.imaging/color) comparison with a defined threshold.
## Methods

| Method | Description |
| --- | --- |
| [invoke(Color p1, Color p2, int threshold)](#invoke-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | Delegate for [Color](../../com.aspose.imaging/color) comparison with a defined threshold. |
### invoke(Color p1, Color p2, int threshold) {#invoke-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public abstract boolean invoke(Color p1, Color p2, int threshold)
```


Delegate for [Color](../../com.aspose.imaging/color) comparison with a defined threshold.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p1 | [Color](../../com.aspose.imaging/color) | The first color to compare. |
| p2 | [Color](../../com.aspose.imaging/color) | The second color to compare. |
| threshold | int | The allowed threshold for color difference. |

**Returns:**
boolean - true if color comparison satisfies the threshold; otherwise, false.
