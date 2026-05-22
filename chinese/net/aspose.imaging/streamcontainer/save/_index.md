---
title: "StreamContainer.Save"
second_title: "Aspose.Imaging for .NET API 参考"
description: "StreamContainer 方法。保存（复制）流的数据到指定的流"
type: docs
weight: 130
url: /zh/net/aspose.imaging/streamcontainer/save/
---
## Save(Stream, int, long) {#save_2}

将流的数据保存（复制）到指定的流。

```csharp
public virtual void Save(Stream destinationStream, int bufferSize, long length)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | Stream | 用于保存数据的流。 |
| bufferSize | Int32 | 缓冲区大小。默认使用 [`ReadWriteBytesCount`](../readwritebytescount/) 的值。 |
| length | Int64 | 要复制的流数据长度。默认情况下，长度设置为 [`Length`](../length/) 的值。 |

### 另请参见

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream) {#save}

保存（复制）流的数据到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../readwritebytescount/) 和流的 [`Length`](../length/) 值。

```csharp
public virtual void Save(Stream destinationStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | Stream | 用于保存数据的流。 |

### 另请参见

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, int) {#save_1}

保存（复制）所有流的数据到指定的流。使用流的 [`Length`](../length/) 值。

```csharp
public virtual void Save(Stream destinationStream, int bufferSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationStream | Stream | 用于保存数据的流。 |
| bufferSize | Int32 | 缓冲区。 |

### 另请参见

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string) {#save_3}

保存（复制）流的数据到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../readwritebytescount/) 和流的 [`Length`](../length/) 值。

```csharp
public virtual void Save(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存流数据的文件路径。 |

### 另请参见

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, int) {#save_4}

保存（复制）流的数据到指定的流。使用流的 [`Length`](../length/) 值。

```csharp
public virtual void Save(string filePath, int bufferSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存流数据的文件路径。 |
| bufferSize | Int32 | 缓冲区大小。默认使用 [`ReadWriteBytesCount`](../readwritebytescount/) 的值。 |

### 另请参见

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, int, long) {#save_5}

将流的数据保存（复制）到指定的流。

```csharp
public virtual void Save(string filePath, int bufferSize, long length)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存流数据的文件路径。 |
| bufferSize | Int32 | 缓冲区大小。默认使用 [`ReadWriteBytesCount`](../readwritebytescount/) 的值。 |
| length | Int64 | 要复制的流数据长度。默认情况下，长度设置为 [`Length`](../length/) 的值。 |

### 另请参见

* class [StreamContainer](../)
* namespace [Aspose.Imaging](../../streamcontainer/)
* assembly [Aspose.Imaging](../../../)


