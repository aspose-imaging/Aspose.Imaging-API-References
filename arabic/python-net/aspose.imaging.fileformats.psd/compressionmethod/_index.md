---
title: "تعداد CompressionMethod"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

يعرف طريقة الضغط المستخدمة لبيانات الصورة.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| RAW | بدون ضغط. يتم تخزين بيانات الصورة كبايتات خام بترتيب RGBA مسطح.<br/>            هذا يعني أنه أولاً تُكتب جميع بيانات R، ثم تُكتب جميع بيانات G، ثم B وأخيراً تُكتب جميع بيانات A. |
| RLE | يتم ضغط البيانات باستخدام RLE حيث يبدأ عدد البايتات لجميع خطوط المسح (الصفوف * القنوات)، مع تخزين كل<br/>            عدد كقيمة من بايتين. تتبع ذلك البيانات المضغوطة بـ RLE، حيث يتم ضغط كل خط مسح على حدة.<br/>            ضغط RLE هو نفس خوارزمية الضغط المستخدمة في روتين ROM الخاص بماكintosh PackBits ومعيار TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP بدون توقع. |
| ZIP_WITH_PREDICTION | ZIP مع توقع. |
