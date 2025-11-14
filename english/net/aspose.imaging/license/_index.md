---
title: Class License
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.License class. Provides methods to license the component
type: docs
weight: 10680
url: /net/aspose.imaging/license/
---
## License class

Provides methods to license the component.

```csharp
public class License
```

## Constructors

| Name | Description |
| --- | --- |
| [License](license/)() | Initializes a new instance of the `License` class. Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [SetLicense](../../aspose.imaging/license/setlicense/#setlicense)(Stream) | Licenses the component. |
| [SetLicense](../../aspose.imaging/license/setlicense/#setlicense_1)(string) | Licenses the component. |

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

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


