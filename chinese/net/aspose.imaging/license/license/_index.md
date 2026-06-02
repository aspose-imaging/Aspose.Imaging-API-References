---
title: "License.License"
second_title: "Aspose.Imaging for .NET API 参考"
description: "License 构造函数。初始化 License 类的新实例。初始化此类的新实例。"
type: docs
weight: 10
url: /zh/net/aspose.imaging/license/license/
---
## License constructor

初始化 [`License`](../) 类的新实例。初始化此类的新实例。

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.Imaging](../../license/)
* assembly [Aspose.Imaging](../../../)


