---
title: "AdaptiveWhiteStretchFilterOptions.AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ AdaptiveWhiteStretchFilterOptions. يهيئ مثلاً جديداً من الفئة AdaptiveWhiteStretchFilter"
type: docs
weight: 10
url: /ar/net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/adaptivewhitestretchfilteroptions/
---
## AdaptiveWhiteStretchFilterOptions constructor

يقوم بإنشاء نسخة جديدة من الفئة AdaptiveWhiteStretchFilter.

```csharp
public AdaptiveWhiteStretchFilterOptions(bool isGrayscale = false, int lowPercentile = 10, 
    int highPercentile = 90, int targetWhite = 240, float maxScale = 1.7)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| isGrayscale | Boolean | يشير إلى ما إذا كان يجب أن يعمل المرشح في وضع تدرج الرمادي. |
| lowPercentile | Int32 | النسبة المئوية الدنيا لنقطة الأسود (مثال: 10). |
| highPercentile | Int32 | النسبة المئوية العليا لنقطة الأبيض (مثال: 90). |
| targetWhite | Int32 | القيمة البيضاء المستهدفة (مثال: 240). |
| maxScale | فردي | الحد الأقصى المسموح لمقياس السطوع (مثال: 1.7). |

## ملاحظات

يقوم الخوارزم بتمديد المخطط التكراري بحيث يقترب النسبة المئوية للون الأبيض من *targetWhite*، ولكن دون تجاوز *maxScale* لتجنب الإضاءة الزائدة.

### انظر أيضًا

* class [AdaptiveWhiteStretchFilterOptions](../)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../adaptivewhitestretchfilteroptions/)
* assembly [Aspose.Imaging](../../../)


