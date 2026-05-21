---
title: "PageExportingAction"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Sayfa dışa aktarılmadan önce tetiklemek için temsilci"
type: docs
weight: 149
url: /tr/java/com.aspose.imaging/pageexportingaction/
---```
public interface PageExportingAction
```

Delegate for firing before page is exported
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageIndex, Image page)](#invoke-int-com.aspose.imaging.Image-) | Delegate for firing before page is exported |
### invoke(int pageIndex, Image page) {#invoke-int-com.aspose.imaging.Image-}
```
public abstract void invoke(int pageIndex, Image page)
```


Delegate for firing before page is exported

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of the page. |
| page | [Image](../../com.aspose.imaging/image) | The page of the multi-page image. |

