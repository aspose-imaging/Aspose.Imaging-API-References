---
title: "تعداد WmfClipPrecisionFlags"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Wmf.Consts.WmfClipPrecisionFlags. تحدد علامات ClipPrecision دقة القطع التي تُعرّف كيفية قطع الأحرف التي تقع جزئياً خارج منطقة القطع. يمكن دمج هذه العلامات لتحديد خيارات متعددة."
type: docs
weight: 8310
url: /ar/net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
## WmfClipPrecisionFlags enumeration

تحدد أعلام ClipPrecision دقة القص، التي تحدد كيفية قص الأحرف التي هي جزئياً خارج منطقة القص. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.

```csharp
[Flags]
public enum WmfClipPrecisionFlags : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Default | `0` | يحدد أنه يجب استخدام القطع الافتراضي. |
| Character | `1` | يجب عدم استخدام هذه القيمة. |
| Stroke | `2` | قد تُرجع هذه القيمة عند تعداد الخطوط الممسوحة ضوئياً، TrueType والخطوط المتجهة. [33] (Windows NT 3.1، Windows NT 3.5، Windows NT 3.51، Windows NT 4.0، Windows 2000، وWindows XP: تُرجع هذه القيمة دائماً عند تعداد الخطوط.) |
| LhAngles | `10` | تُستخدم هذه القيمة للتحكم في دوران الخطوط، كما يلي: - إذا تم تعيينها، يجب أن يُحدَّد دوران جميع الخطوط بناءً على اتجاه نظام الإحداثيات؛ أي ما إذا كان الاتجاه يساريًا أم يمينيًا. - إذا لم تُعيّن، يجب أن تدور خطوط الجهاز عكس اتجاه عقارب الساعة، لكن يجب أن يُحدَّد دوران الخطوط الأخرى بناءً على اتجاه نظام الإحداثيات. |
| TtAlways | `20` | يجب عدم استخدام هذه القيمة [34]. [34] تُهمل هذه القيمة في إصدارات Windows التالية: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| DfaDisable | `40` | تحدد هذه القيمة أن ارتباط الخط يجب أن يُعطَّل [35]. [35] لا يتم دعم هذه القيمة في Windows 95 وWindows 98 وWindows Millennium Edition. يتم إيقاف ارتباط الخط في Windows 2000 وWindows XP وWindows Server 2003. تُهمل هذه القيمة في إصدارات Windows التالية: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| Embedded | `80` | تحدد هذه القيمة أنه يجب استخدام تضمين الخطوط لتصيير محتوى المستند؛ الخطوط المضمَّنة للقراءة فقط. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


