---
title: "TiffStreamReader.ReadBytes"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffStreamReader. قراءة مصفوفة من قيم byte من الدفق"
type: docs
weight: 40
url: /ar/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readbytes/
---
## ReadBytes(byte[], int, long, long) {#readbytes_1}

يقرأ مصفوفة من قيم البايت من التيار.

```csharp
public long ReadBytes(byte[] array, int arrayIndex, long position, long count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| array | Byte[] | المصفوفة التي سيتم ملؤها. |
| arrayIndex | Int32 | فهرس المصفوفة للبدء بوضع القيم فيه. |
| الموضع | Int64 | موضع الدفق للقراءة منه. |
| count | Int64 | عدد العناصر للقراءة. |

### قيمة الإرجاع

مصفوفة قيم byte.

### انظر أيضًا

* class [TiffStreamReader](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assembly [Aspose.Imaging](../../../)

---

## ReadBytes(long, long) {#readbytes}

يقرأ مصفوفة من قيم البايت غير الموقعة من التيار.

```csharp
public byte[] ReadBytes(long position, long count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضع | Int64 | الموضع للقراءة منه. |
| count | Int64 | عدد العناصر. |

### قيمة الإرجاع

مصفوفة قيم byte غير موقعة.

### انظر أيضًا

* class [TiffStreamReader](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assembly [Aspose.Imaging](../../../)


