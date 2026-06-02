---
title: "FileStreamContainer.IsTemporal"
second_title: "Aspose.Imaging for .NET API 参考"
description: "FileStreamContainer 属性。获取或设置指示流是否为临时的值"
type: docs
weight: 50
url: /zh/net/aspose.imaging/filestreamcontainer/istemporal/
---
## FileStreamContainer.IsTemporal property

获取或设置一个值，指示流是否为临时的。

```csharp
public bool IsTemporal { get; set; }
```

### Property Value

`true` 表示流是临时的；否则为 `false`。

## 备注

临时流在释放时会自行移除。如果流是基于内存的，则此属性无效。可以将流标记为临时或持久，前提是它是显式创建的，否则会抛出相应的异常。

### 另请参见

* class [FileStreamContainer](../)
* namespace [Aspose.Imaging](../../filestreamcontainer/)
* assembly [Aspose.Imaging](../../../)


