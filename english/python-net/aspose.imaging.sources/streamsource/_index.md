---
title: StreamSource Class
type: docs
weight: 40
url: /python-net/aspose.imaging.sources/streamsource/
---

Represents a stream source.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.StreamSource

**Inheritance:** Source

**Aspose.Imaging Version:** 23.6

The StreamSource type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [StreamSource()](#StreamSource__0) | Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class. |
| [StreamSource(stream)](#StreamSource_stream_1) | Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class. |
| [StreamSource(stream, dispose_stream)](#StreamSource_stream_dispose_stream_2) | Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| stream | _io.BufferedRandom | r | Gets the stream. |
| dispose_stream | bool | r | Gets a value indicating whether stream should be disposed whenever container gets disposed. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__3) | Gets the stream container. |

### StreamSource() {#StreamSource__0}


```
 StreamSource() 
```

Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class.

### StreamSource(stream) {#StreamSource_stream_1}


```
 StreamSource(stream) 
```

Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to open. |

### StreamSource(stream, dispose_stream) {#StreamSource_stream_dispose_stream_2}


```
 StreamSource(stream, dispose_stream) 
```

Initializes a new instance of the [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to open. |
| dispose_stream | bool | if set to <c>true</c> the stream will be disposed. |

### get_stream_container() {#get_stream_container__3}


```
 get_stream_container() 
```

Gets the stream container.

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | the stream container. |


