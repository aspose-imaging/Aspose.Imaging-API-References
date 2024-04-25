---
title: StreamContainer
second_title: Aspose.Imaging for .NET API Referansı
description: Akışı içeren ve akış işleme rutinleri sağlayan akış kapsayıcısını temsil eder.
type: docs
weight: 11130
url: /tr/aspose.imaging/streamcontainer/
---
## StreamContainer class

Akışı içeren ve akış işleme rutinleri sağlayan akış kapsayıcısını temsil eder.

```csharp
public class StreamContainer : DisposableObject
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Yeni bir örneğini başlatır[`StreamContainer`](../streamcontainer) sınıf. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Yeni bir örneğini başlatır[`StreamContainer`](../streamcontainer) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Akışın okumayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Akışın aramayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Akışın yazmayı destekleyip desteklemediğini gösteren bir değer alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Bu akışın kapanışta atılıp atılmadığını gösteren bir değer alır. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer daha küçükLength StreamContainer yapıcısında geçirilen başlangıç akış konumu tarafından. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısında geçirilen başlangıç akış konumundan farkı temsil eder. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Senkronize kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Bu akış için tüm arabellekleri temizler ve arabelleğe alınan verilerin temel alınan aygıta yazılmasına neden olur. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read)(byte[]) | Belirtilen bayt arabelleğini doldurmak için baytları okur. |
| virtual [Read](../../aspose.imaging/streamcontainer/read#read_1)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir veya akışın sonundaysa -1 döndürür. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](./readwritebytescount) ve akış[`Length`](./length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_3)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](./readwritebytescount) ve akış[`Length`](./length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_1)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akışı kullanır[`Length`](./length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_4)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akışı kullanır[`Length`](./length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_2)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.imaging/streamcontainer/save#save_5)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısında geçirilen başlangıç akış konumundan farkı temsil eder. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes)() | Akış verileriniByte dizi. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes#tobytes_1)(long, long) | Akış verileriniByte dizi. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| virtual [Write](../../aspose.imaging/streamcontainer/write#write_1)(byte[], int, int) | Geçerli akışa bir bayt dizisi yazar ve bu akış içindeki geçerli konumu, yazılan bayt sayısı kadar ilerletir. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Akıştaki geçerli konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto)(StreamContainer) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto#writeto_1)(StreamContainer, long) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/streamcontainer/op_explicit) | Şundan açık bir dönüştürme gerçekleştirir:[`StreamContainer`](../streamcontainer) ileStream . |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.imaging/streamcontainer/readwritebytescount) | Sıralı olarak okurken okuma ve yazma bayt sayısını belirtir. |

### Ayrıca bakınız

* class [DisposableObject](../disposableobject)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
