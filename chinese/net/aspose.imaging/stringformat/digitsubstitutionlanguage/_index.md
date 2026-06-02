---
title: "StringFormat.DigitSubstitutionLanguage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "StringFormat 属性。获取或设置在本地数字替换为西方数字时使用的语言。"
type: docs
weight: 60
url: /zh/net/aspose.imaging/stringformat/digitsubstitutionlanguage/
---
## StringFormat.DigitSubstitutionLanguage property

获取或设置在本地数字替换为西方数字时使用的语言。

```csharp
public int DigitSubstitutionLanguage { get; set; }
```

### Property Value

一个国家语言支持 (NLS) 语言标识符，用于标识在本地数字替换为西方数字时将使用的语言。您可以将 CultureInfo 对象的 LCID 属性作为 NLS 语言标识符传递。例如，假设您通过将字符串 "ar-EG" 传递给 CultureInfo 构造函数来创建一个 CultureInfo 对象。如果将该 CultureInfo 对象的 LCID 属性与 StringDigitSubstitute 方法一起传递，则阿拉伯-印度数字将在显示时被替换为西方数字。

## 备注

为已废弃的方法 SetDigitSubstitution 引入了 setter。

### 另请参见

* class [StringFormat](../)
* namespace [Aspose.Imaging](../../stringformat/)
* assembly [Aspose.Imaging](../../../)


