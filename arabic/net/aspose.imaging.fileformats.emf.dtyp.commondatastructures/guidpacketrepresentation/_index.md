---
title: "الهيكل GuidPacketRepresentation"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الهيكل Aspose.Imaging.FileFormats.Emf.Dtyp.CommonDataStructures.GuidPacketRepresentation. يُستخدم إصدار الحزمة ضمن بروتوكولات الكتلة. يمثل المخطط التالي GUID كسلسلة شفافة من البايتات. GUID المعروف أيضًا باسم UUID هو بنية بطول 16 بايت تُستخدم كمعرف فريد لكائن. هناك ثلاث تمثيلات لـ GUID كما هو موضح في الأقسام التالية."
type: docs
weight: 2620
url: /ar/net/aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
## GuidPacketRepresentation structure

إصدار الحزمة يُستخدم داخل بروتوكولات الكتلة. المخطط التالي يمثل GUID كسلسلة غير شفافة من البايتات. GUID، المعروف أيضًا باسم UUID، هو بنية مكونة من 16 بايت، يُقصد به أن يكون معرفًا فريدًا لكائن. هناك ثلاث تمثيلات لـ GUID، كما هو موضح في الأقسام التالية.

```csharp
public struct GuidPacketRepresentation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GuidPacketRepresentation](guidpacketrepresentation/)(int, short, short, long) | ينشئ مثيلًا جديدًا للهيكل `GuidPacketRepresentation`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Data1](../../aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/data1/) { get; set; } | يحصل أو يعيّن قيمة العضو Data1 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [Data2](../../aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/data2/) { get; set; } | يحصل أو يعيّن قيمة العضو Data2 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [Data3](../../aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/data3/) { get; set; } | يحصل أو يضبط قيمة العضو Data3 (القسم 2.3.4)، بترتيب البايتات little-endian. |
| [Data4](../../aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/data4/) { get; set; } | يحصل أو يضبط قيمة العضو Data4 (القسم 2.3.4)، بترتيب البايتات little-endian. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ToString](../../aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Dtyp.CommonDataStructures](../../aspose.imaging.fileformats.emf.dtyp.commondatastructures/)
* assembly [Aspose.Imaging](../../)


