---
title: ImageAttributes.SetOutputChannelColorProfile
second_title: Aspose.Imaging for .NET API Reference
description: ImageAttributes method. Sets the output channel colorprofile file for the default category
type: docs
weight: 180
url: /net/aspose.imaging/imageattributes/setoutputchannelcolorprofile/
---
## SetOutputChannelColorProfile(string) {#setoutputchannelcolorprofile}

Sets the output channel color-profile file for the default category.

```csharp
public void SetOutputChannelColorProfile(string colorProfileFilename)
```

| Parameter | Type | Description |
| --- | --- | --- |
| colorProfileFilename | String | The path name of a color-profile file. If the color-profile file is in the %SystemRoot%\System32\Spool\Drivers\Color directory, this parameter can be the file name. Otherwise, this parameter must be the fully qualified path name. |

### See Also

* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)

---

## SetOutputChannelColorProfile(string, ColorAdjustType) {#setoutputchannelcolorprofile_1}

Sets the output channel color-profile file for a specified category.

```csharp
public void SetOutputChannelColorProfile(string colorProfileFilename, ColorAdjustType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| colorProfileFilename | String | The path name of a color-profile file. If the color-profile file is in the %SystemRoot%\System32\Spool\Drivers\Color directory, this parameter can be the file name. Otherwise, this parameter must be the fully qualified path name. |
| type | ColorAdjustType | An element of [`ColorAdjustType`](../../coloradjusttype/) that specifies the category for which the output channel color-profile file is set. |

### See Also

* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)


