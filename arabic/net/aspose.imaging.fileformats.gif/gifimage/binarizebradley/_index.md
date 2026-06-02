---
title: "GifImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة هو طريقة لتحويل صورة ذات تدرج رمادي إلى صورة ثنائية. تحسب هذه الخوارزمية عتبة محلية لكل بكسل بناءً على متوسط شدة البكسلات المحيطة ضمن نافذة محددة. من خلال تعديل العتبة بشكل تكيفي بناءً على شدة البكسلات المحلية يكون أسلوب برايدلي فعالًا في التعامل مع تباينات الإضاءة والتباين عبر الصورة."
type: docs
weight: 240
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/binarizebradley/
---
## GifImage.BinarizeBradley method

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة هو طريقة لتحويل صورة رمادية إلى صورة ثنائية. تحسب هذه الخوارزمية عتبة محلية لكل بكسل بناءً على متوسط شدة البكسلات المحيطة داخل نافذة محددة. من خلال تعديل العتبة محليًا بناءً على شدة البكسلات، تكون طريقة برايدلي فعّالة في التعامل مع تباينات الإضاءة والظلال عبر الصورة.

```csharp
public override void BinarizeBradley(double brightnessDifference)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل. |

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


