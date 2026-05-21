---
title: "الفئة AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageFilters.FilterOptions.AdaptiveWhiteStretchFilterOptions. يوفر خيارات لتكوين مرشح التمدد الأبيض التكيفي. يسمح بتخصيص معلمات تمدد المدرج التكراري لتعزيز مستوى الأبيض وتحسين قابلية قراءة النص الخافت أو صور المستندات ذات التباين المنخفض."
type: docs
weight: 9940
url: /ar/net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
## AdaptiveWhiteStretchFilterOptions class

يوفر خيارات لتكوين مرشح Adaptive White Stretch. يسمح بتخصيص معلمات تمديد المدرج التكراري لتعزيز مستوى الأبيض وتحسين قابلية قراءة النص الضعيف أو صور المستند ذات التباين المنخفض.

```csharp
public class AdaptiveWhiteStretchFilterOptions : FilterOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions](adaptivewhitestretchfilteroptions/)(bool, int, int, int, float) | يقوم بإنشاء نسخة جديدة من الفئة AdaptiveWhiteStretchFilter. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HighPercentile](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/highpercentile/) { get; } | يحصل على النسبة المئوية العليا لحساب نقطة الأبيض. تُعتبر قيم البكسل التي فوق هذه النسبة بيضاء أثناء التمدد. |
| [IsGrayscale](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/isgrayscale/) { get; } | يحصل على قيمة تشير إلى ما إذا كان المرشح يعمل في وضع التدرج الرمادي. |
| [LowPercentile](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/lowpercentile/) { get; } | يحصل على النسبة المئوية السفلى لحساب نقطة السواد. تُعتبر قيم البكسل التي تحت هذه النسبة سوداء أثناء التمدد. |
| [MaxScale](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/maxscale/) { get; } | يحصل على أقصى مقياس سطوع مسموح به. لن يتجاوز التمدد الفعلي هذا العامل لتجنب الإضاءة الزائدة. |
| [TargetWhite](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/targetwhite/) { get; } | يحصل على قيمة الأبيض المستهدفة التي يهدف التمدد إلى تحقيقها. |

### انظر أيضًا

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


