---
title: "License.SetLicense"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة License. تُرخص المكوّن."
type: docs
weight: 20
url: /ar/net/aspose.imaging/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licenseName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

## ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (البدء).

5. مورد مضمن في تجميع الاستدعاء الخاص بالعميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مضمن في تجميع الاستدعاء الخاص بالعميل.

## أمثلة

في هذا المثال، سيتم محاولة العثور على ملف الترخيص المسمى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المضمنة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Imaging](../../license/)
* assembly [Aspose.Imaging](../../../)

---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق يحتوي على الترخيص. |

## ملاحظات

استخدم هذه الطريقة لتحميل الترخيص من دفق.

## أمثلة

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Imaging](../../license/)
* assembly [Aspose.Imaging](../../../)


