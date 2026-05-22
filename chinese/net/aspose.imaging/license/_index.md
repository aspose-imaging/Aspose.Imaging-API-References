---
title: "类 License"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.License 类。提供对组件授权的方法"
type: docs
weight: 10750
url: /zh/net/aspose.imaging/license/
---
## License class

提供对组件授权的方法。

```csharp
public class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license/)() | 初始化 `License` 类的新实例。初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.imaging/license/setlicense/#setlicense)(Stream) | 为组件授权。 |
| [SetLicense](../../aspose.imaging/license/setlicense/#setlicense_1)(string) | 为组件授权。 |

## 示例

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹中查找名为 MyLicense.lic 的许可证文件，随后在调用程序集的嵌入资源中查找。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


