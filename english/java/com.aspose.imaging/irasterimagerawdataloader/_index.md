---
title: IRasterImageRawDataLoader
second_title: Aspose.Imaging for Java API Reference
description: The raster image raw data loader.
type: docs
weight: 148
url: /java/com.aspose.imaging/irasterimagerawdataloader/
---```
public interface IRasterImageRawDataLoader
```

The raster image raw data loader.
## Methods

| Method | Description |
| --- | --- |
| [isRawDataAvailable()](#isRawDataAvailable--) | Gets a value indicating whether raw data loading is supported. |
| [getRawDataSettings()](#getRawDataSettings--) | Gets the current raw data settings. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Loads raw data. |
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Gets a value indicating whether raw data loading is supported.

**Returns:**
boolean - `true` if raw data loading is supported; otherwise, `false`.
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Gets the current raw data settings. Note when using these settings the data loads without conversion.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings) - The current raw data settings.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Loads raw data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle to load raw data from. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | The raw data loader. |

