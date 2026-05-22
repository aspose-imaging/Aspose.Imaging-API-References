---
title: "PsdOptions.RemoveGlobalTextEngineResource"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PsdOptions 属性。获取或设置一个值，指示是否 移除全局文本引擎资源 该选项用于某些带有文本层的 psd 文件，仅在处理后无法在 Adobe Photoshop 中打开时，通常因为缺少字体的文本层。使用此选项后，用户需要在 Photoshop 打开的文件中依次选择 菜单 文本 处理缺失字体。完成该操作后，所有文本将再次出现。请注意，此操作可能导致最终布局出现一些更改"
type: docs
weight: 80
url: /zh/net/aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource/
---
## PsdOptions.RemoveGlobalTextEngineResource property

获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本层的 psd 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 "Text" -> "Process absent fonts"。该操作完成后，所有文本将再次出现。请注意，此操作可能导致一些最终布局的更改。

```csharp
public bool RemoveGlobalTextEngineResource { get; set; }
```

### Property Value

`true` 如果 [remove global text engine resource]；否则，`false`。

### 另请参见

* class [PsdOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../psdoptions/)
* assembly [Aspose.Imaging](../../../)


