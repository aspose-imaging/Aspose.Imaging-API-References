---
title: IPartialRawDataLoader
second_title: Aspose.Imaging for Java API Reference
description: The partial data loader.
type: docs
weight: 144
url: /java/com.aspose.imaging/ipartialrawdataloader/
---```
public interface IPartialRawDataLoader
```

The partial data loader.
## Methods

| Method | Description |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.imaging.Rectangle-byte---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Processes the loaded data. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.imaging.Rectangle-byte---com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.LoadOptions-) | Processes the loaded data. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.imaging.Rectangle-byte---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Processes the loaded data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The data rectangle. |
| data | byte[] | The raw data. |
| start | [Point](../../com.aspose.imaging/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.imaging/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.imaging.Rectangle-byte---com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Processes the loaded data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The data rectangle. |
| data | byte[] | The raw data. |
| start | [Point](../../com.aspose.imaging/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.imaging/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

