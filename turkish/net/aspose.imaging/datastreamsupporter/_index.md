---
title: DataStreamSupporter
second_title: Aspose.Imaging for .NET API Referansı
description: Veri akışı kapsayıcısı.
type: docs
weight: 810
url: /tr/net/aspose.imaging/datastreamsupporter/
---
## DataStreamSupporter class

Veri akışı kapsayıcısı.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumasının gerekip gerekmediğini gösteren bir değer alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](./datastreamcontainer) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save)() | Nesnenin verilerini geçerli[`DataStreamSupporter`](../datastreamsupporter) . |
| [Save](../../aspose.imaging/datastreamsupporter/save#save_1)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_2)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save#save_3)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |

### Ayrıca bakınız

* class [DisposableObject](../disposableobject)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
