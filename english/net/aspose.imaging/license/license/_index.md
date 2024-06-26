---
title: License.License
second_title: Aspose.Imaging for .NET API Reference
description: License constructor. Initializes a new instance of the License class. Initializes a new instance of this class
type: docs
weight: 10
url: /net/aspose.imaging/license/license/
---
## License constructor

Initializes a new instance of the [`License`](../) class. Initializes a new instance of this class.

```csharp
public License()
```

## Examples

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### See Also

* class [License](../)
* namespace [Aspose.Imaging](../../license/)
* assembly [Aspose.Imaging](../../../)


