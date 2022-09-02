---
title: FileStreamContainer
second_title: Aspose.Imaging for .NET API Referansı
description: Dosya akışı işleme için yardımcı.
type: docs
weight: 9300
url: /tr/net/aspose.imaging/filestreamcontainer/
---
## FileStreamContainer class

Dosya akışı işleme için yardımcı.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [CanRead](../../aspose.imaging/streamcontainer/canread) { get; } | Akışın okumayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanSeek](../../aspose.imaging/streamcontainer/canseek) { get; } | Akışın aramayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanWrite](../../aspose.imaging/streamcontainer/canwrite) { get; } | Akışın yazmayı destekleyip desteklemediğini gösteren bir değer alır. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FilePath](../../aspose.imaging/filestreamcontainer/filepath) { get; } | Dosya yolunu alır. |
| [IsCreated](../../aspose.imaging/filestreamcontainer/iscreated) { get; } | Akışın açıkça oluşturulup oluşturulmadığını gösteren bir değer alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.imaging/streamcontainer/isstreamdisposedonclose) { get; } | Bu akışın kapanışta atılıp atılmadığını gösteren bir değer alır. |
| [IsTemporal](../../aspose.imaging/filestreamcontainer/istemporal) { get; set; } | Akışın geçici olup olmadığını belirten bir değer alır veya ayarlar. |
| virtual [Length](../../aspose.imaging/streamcontainer/length) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer daha küçükLength StreamContainer yapıcısında geçirilen başlangıç akış konumu tarafından. |
| virtual [Position](../../aspose.imaging/streamcontainer/position) { get; set; } | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısında geçirilen başlangıç akış konumundan farkı temsil eder. |
| virtual [Stream](../../aspose.imaging/streamcontainer/stream) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.imaging/streamcontainer/syncroot) { get; } | Senkronize kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [CreateFileStream](../../aspose.imaging/filestreamcontainer/createfilestream)(string, bool) | Yeni bir dosya akışı oluşturur. |
| static [OpenFileStream](../../aspose.imaging/filestreamcontainer/openfilestream)(string) | Var olan bir dosya akışını açar. Dosya akışı yoksa uygun istisna atılır. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| virtual [Flush](../../aspose.imaging/streamcontainer/flush)() | Bu akış için tüm arabellekleri temizler ve arabelleğe alınan verilerin temel alınan aygıta yazılmasına neden olur. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[]) | Belirtilen bayt arabelleğini doldurmak için baytları okur. |
| virtual [Read](../../aspose.imaging/streamcontainer/read)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| virtual [ReadByte](../../aspose.imaging/streamcontainer/readbyte)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir veya akışın sonundaysa -1 döndürür. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) ve akış[`Length`](../streamcontainer/length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) ve akış[`Length`](../streamcontainer/length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akışı kullanır[`Length`](../streamcontainer/length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akışı kullanır[`Length`](../streamcontainer/length) değer. |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.imaging/streamcontainer/save)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Seek](../../aspose.imaging/streamcontainer/seek)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| virtual [SeekBegin](../../aspose.imaging/streamcontainer/seekbegin)() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısında geçirilen başlangıç akış konumundan farkı temsil eder. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)() | Akış verileriniByte dizi. |
| virtual [ToBytes](../../aspose.imaging/streamcontainer/tobytes)(long, long) | Akış verileriniByte dizi. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| virtual [Write](../../aspose.imaging/streamcontainer/write)(byte[], int, int) | Geçerli akışa bir bayt dizisi yazar ve bu akış içindeki geçerli konumu, yazılan bayt sayısı kadar ilerletir. |
| virtual [WriteByte](../../aspose.imaging/streamcontainer/writebyte)(byte) | Akıştaki geçerli konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.imaging/streamcontainer/writeto)(StreamContainer, long) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.imaging/filestreamcontainer/op_explicit#op_explicit_1) | Şundan açık bir dönüştürme gerçekleştirir:[`FileStreamContainer`](../filestreamcontainer) ileStream . (2 operators) |

### Ayrıca bakınız

* class [StreamContainer](../streamcontainer)
* ad alanı [Aspose.Imaging](../../aspose.imaging)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
