---
title: StreamContainer.Save
second_title: Aspose.Imaging for .NET API Reference
description: StreamContainer method. Saves copies the streams data to the specified stream. Uses default buffer size ReadWriteBytesCount and stream Length value
type: docs
weight: 130
url: /net/aspose.imaging/streamcontainer/save/
---
## Save(Stream) {#save}

Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../readwritebytescount/) and stream [`Length`](../length/) value.

```csharp
public virtual void Save(Stream destinationStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | Stream | The stream to save the data to. |

### See Also

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, int) {#save_1}

Saves (copies) all the stream's data to the specified stream. Uses stream [`Length`](../length/) value.

```csharp
public virtual void Save(Stream destinationStream, int bufferSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | Stream | The stream to save the data to. |
| bufferSize | Int32 | The buffer. |

### See Also

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, int, long) {#save_2}

Saves (copies) the stream's data to the specified stream.

```csharp
public virtual void Save(Stream destinationStream, int bufferSize, long length)
```

| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | Stream | The stream to save the data to. |
| bufferSize | Int32 | The buffer size. By default [`ReadWriteBytesCount`](../readwritebytescount/) value is used. |
| length | Int64 | The stream data length to copy. By default the length is set to [`Length`](../length/) value. |

### See Also

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string) {#save_3}

Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../readwritebytescount/) and stream [`Length`](../length/) value.

```csharp
public virtual void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to save the stream data to. |

### See Also

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, int) {#save_4}

Saves (copies) the stream's data to the specified stream. Uses stream [`Length`](../length/) value.

```csharp
public virtual void Save(string filePath, int bufferSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to save the stream data to. |
| bufferSize | Int32 | The buffer size. By default [`ReadWriteBytesCount`](../readwritebytescount/) value is used. |

### See Also

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, int, long) {#save_5}

Saves (copies) the stream's data to the specified stream.

```csharp
public virtual void Save(string filePath, int bufferSize, long length)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to save the stream data to. |
| bufferSize | Int32 | The buffer size. By default [`ReadWriteBytesCount`](../readwritebytescount/) value is used. |
| length | Int64 | The stream data length to copy. By default the length is set to [`Length`](../length/) value. |

### See Also

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)


