---
title: "WmfClipPrecisionFlags Enumeration"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

تحدد أعلام ClipPrecision دقة القص، والتي تحدد كيفية قص الأحرف التي تكون<br/>                جزئيًا خارج منطقة القص. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| CHARACTER | يجب عدم استخدام هذه القيمة. |
| افتراضي | يحدد أنه يجب استخدام القص الافتراضي. |
| DFA_DISABLE | تحدد هذه القيمة أن ارتباط الخط يجب أن يكون معطلاً [35].<br/>                [35] هذه القيمة غير مدعومة في Windows 95 و Windows 98 و Windows Millennium Edition.<br/>                يتم إيقاف ارتباط الخط في Windows 2000 و Windows XP و Windows Server 2003.<br/>                يتم تجاهل هذه القيمة في إصدارات Windows التالية:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
| EMBEDDED | تحدد هذه القيمة أنه يجب استخدام تضمين الخطوط لتصيير محتوى المستند<br/>               ؛ الخطوط المضمنة للقراءة فقط. |
| LH_ANGLES | تُستخدم هذه القيمة للتحكم في دوران الخطوط كما يلي:<br/>                - إذا تم تعيينها، يجب أن يُحدد دوران جميع الخطوط وفقًا لاتجاه نظام الإحداثيات؛ أي ما إذا كان الاتجاه يدًا يسرى أو يدًا يمنى.<br/>                - إذا لم تُحدد، يجب أن تدور خطوط الجهاز عكس اتجاه عقارب الساعة، لكن يجب أن يُحدد دوران الخطوط الأخرى وفقًا لاتجاه نظام الإحداثيات. |
| STROKE | قد تُرجع هذه القيمة عند تعداد الخطوط المرسومة، TrueType و<br/>                الخطوط المتجهية.<br/>                [33] (Windows NT 3.1، Windows NT 3.5، Windows NT 3.51، Windows NT 4.0،<br/>                Windows 2000، و Windows XP: تُرجع هذه القيمة دائمًا عند تعداد الخطوط.) |
| TT_ALWAYS | يجب عدم استخدام هذه القيمة [34].<br/>                [34] يتم تجاهل هذه القيمة في إصدارات Windows التالية:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
