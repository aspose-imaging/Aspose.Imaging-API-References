---
title: SplitStreamContainer
second_title: Aspose.Imaging for .NET API Referansı
description: Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış kapsayıcısını temsil eder.
type: docs
weight: 11120
url: /tr/net/aspose.imaging/splitstreamcontainer/
---
## SplitStreamContainer class

Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış kapsayıcısını temsil eder.

```csharp
public class SplitStreamContainer : StreamContainer
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Yeni bir örneğini başlatır[`SplitStreamContainer`](../splitstreamcontainer) sınıf. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Yeni bir örneğini başlatır[`SplitStreamContainer`](../splitstreamcontainer) sınıf. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Yeni bir örneğini başlatır[`SplitStreamContainer`](../splitstreamcontainer) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [CanRead](../../aspose.imaging/splitstreamcontainer/canread) { get; } | Akışın okumayı destekleyip desteklemediğini gösteren bir değer alır. |
| override [CanSeek](../../aspose.imaging/splitstreamcontainer/canseek) { get; } | Akışın aramayı destekleyip desteklemediğini gösteren bir değer alır. |
| override [CanWrite](../../aspose.imaging/splitstreamcontainer/canwrite) { get; } | Akışın yazmayı destekleyip desteklemediğini gösteren bir değer alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Bu akışın kapanışta atılıp atılmadığını gösteren bir değer alır. |
| override [Length](../../aspose.imaging/splitstreamcontainer/length) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer daha küçükLength StreamContainer yapıcısında geçirilen başlangıç akış konumu tarafından. |
| override [Position](../../aspose.imaging/splitstreamcontainer/position) { get; set; } | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısında geçirilen başlangıç akış konumundan farkı temsil eder. |
| override [Stream](../../aspose.imaging/splitstreamcontainer/stream) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.imaging/splitstreamcontainer/syncroot) { get; } | Senkronize kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| override [Flush](../../aspose.imaging/splitstreamcontainer/flush)() | Bu akış için tüm arabellekleri temizler ve arabelleğe alınan verilerin temel alınan aygıta yazılmasına neden olur. |
| [Insert](../../aspose.imaging/splitstreamcontainer/insert)(int, StreamContainer, bool) | Akış kapsayıcısını belirtilen konuma ekler. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read)(byte[]) | Belirtilen bayt arabelleğini doldurmak için baytları okur. |
| override [Read](../../aspose.imaging/splitstreamcontainer/read#read_1)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| override [ReadByte](../../aspose.imaging/splitstreamcontainer/readbyte)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir veya akışın sonundaysa -1 döndürür. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) ve akış[`Length`](../streamcontainer/length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) ve akış[`Length`](../streamcontainer/length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akışı kullanır[`Length`](../streamcontainer/length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akışı kullanır[`Length`](../streamcontainer/length) değer. |
| override [Save](../../aspose.imaging/splitstreamcontainer/save#save_2)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| override [Seek](../../aspose.imaging/splitstreamcontainer/seek)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| override [SeekBegin](../../aspose.imaging/splitstreamcontainer/seekbegin)() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısında geçirilen başlangıç akış konumundan farkı temsil eder. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes)() | Akış verileriniByte dizi. |
| override [ToBytes](../../aspose.imaging/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Akış verileriniByte dizi. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| override [Write](../../aspose.imaging/splitstreamcontainer/write#write_1)(byte[], int, int) | Geçerli akışa bir bayt dizisi yazar ve bu akış içindeki geçerli konumu, yazılan bayt sayısı kadar ilerletir. |
| override [WriteByte](../../aspose.imaging/splitstreamcontainer/writebyte)(byte) | Akıştaki geçerli konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer) . |

### Ayrıca bakınız

* class [StreamContainer](../streamcontainer)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
