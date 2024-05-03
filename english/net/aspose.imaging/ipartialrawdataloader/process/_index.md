---
title: IPartialRawDataLoader.Process
second_title: Aspose.Imaging for .NET API Reference
description: IPartialRawDataLoader method. Processes the loaded data
type: docs
weight: 10
url: /net/aspose.imaging/ipartialrawdataloader/process/
---
## Process(Rectangle, byte[], Point, Point) {#process}

Processes the loaded data.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The data rectangle. |
| data | Byte[] | The raw data. |
| start | Point | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | Point | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

### See Also

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.Imaging](../../ipartialrawdataloader/)
* assembly [Aspose.Imaging](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Processes the loaded data.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The data rectangle. |
| data | Byte[] | The raw data. |
| start | Point | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | Point | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |
| loadOptions | LoadOptions | The load options. |

### See Also

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.Imaging](../../ipartialrawdataloader/)
* assembly [Aspose.Imaging](../../../)


