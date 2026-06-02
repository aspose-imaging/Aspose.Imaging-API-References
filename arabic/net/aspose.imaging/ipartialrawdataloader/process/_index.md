---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة IPartialRawDataLoader. يعالج البيانات المحملة"
type: docs
weight: 10
url: /ar/net/aspose.imaging/ipartialrawdataloader/process/
---
## Process(Rectangle, byte[], Point, Point) {#process}

يعالج البيانات المحملة.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | مستطيل البيانات. |
| بيانات | Byte[] | البيانات الخام. |
| بدء | Point | نقطة بدء البيانات. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| نهاية | Point | نقطة نهاية البيانات. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.Imaging](../../ipartialrawdataloader/)
* assembly [Aspose.Imaging](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

يعالج البيانات المحملة.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | مستطيل البيانات. |
| بيانات | Byte[] | البيانات الخام. |
| بدء | Point | نقطة بدء البيانات. إذا لم تكن مساوية لـ (left,top) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| نهاية | Point | نقطة نهاية البيانات. إذا لم تكن مساوية لـ (right,bottom) فهذا يعني أنها ليست مستطيلًا كاملًا لدينا. |
| loadOptions | LoadOptions | خيارات التحميل. |

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.Imaging](../../ipartialrawdataloader/)
* assembly [Aspose.Imaging](../../../)


