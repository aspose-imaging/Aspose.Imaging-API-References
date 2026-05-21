---
title: "الفئة License"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.License. توفر طرقًا لترخيص المكوّن"
type: docs
weight: 10750
url: /ar/net/aspose.imaging/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license/)() | يُهيئ نسخة جديدة من الفئة `License`. يُهيئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.imaging/license/setlicense/#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.imaging/license/setlicense/#setlicense_1)(string) | يرخص المكوّن. |

## أمثلة

في هذا المثال، سيتم محاولة العثور على ملف الترخيص المسمى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المضمنة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


