---
title: "الفئة AutoWhiteBalanceFilterOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageFilters.FilterOptions.AutoWhiteBalanceFilterOptions. يوفر خيارات تكوين لمرشح التوازن الأبيض التلقائي. يسمح بضبط معلمات تمديد التباين وتوسيع القنوات لتحسين مظهر الصور الرقمية."
type: docs
weight: 9950
url: /ar/net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
## AutoWhiteBalanceFilterOptions class

يوفر خيارات تكوين لمرشح Auto White Balance. يسمح بضبط معلمات تمديد التباين وتوسيع القنوات لتحسين مظهر الصور الرقمية.

```csharp
public class AutoWhiteBalanceFilterOptions : FilterOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AutoWhiteBalanceFilterOptions](autowhitebalancefilteroptions/)(int, int, int, float, int) | يقوم بإنشاء نسخة جديدة من الفئة `AutoWhiteBalanceFilterOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [LowPercentile](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/lowpercentile/) { get; } | النسبة المئوية المنخفضة لنقطة السواد، تُستخدم لحماية الظلال (الافتراضي: 3). |
| [MaxScale](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/maxscale/) { get; } | يحصل على أقصى عامل تكبير لكل قناة. يحد من تضخيم أي قناة لتجنب التحولات اللونية المفرطة. |
| [ProtectedDarkOffset](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/protecteddarkoffset/) { get; } | الإزاحة من النسبة المئوية المنخفضة التي أدناها لا يتم تمديد البكسلات الداكنة (حماية). |
| [TargetHighPercentile](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/targethighpercentile/) { get; } | يحصل على النسبة المئوية العليا المستهدفة لتمديد التباين. يحدد أي نسبة إضاءة سيتم ربطها بالقيمة المستهدفة. |
| [TargetValue](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/targetvalue/) { get; } | يحصل على القيمة المستهدفة للنسبة المئوية العليا. ستُستخدم هذه القيمة كمرجع أبيض لتمديد التباين. |

### انظر أيضًا

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


