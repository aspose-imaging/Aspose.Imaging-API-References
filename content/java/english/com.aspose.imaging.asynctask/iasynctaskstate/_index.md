---
title: IAsyncTaskState
second_title: Aspose.Imaging for Java API Reference
description: Provides access to the state of the asynchronous task.
type: docs
weight: 17
url: /com.aspose.imaging.asynctask/iasynctaskstate/
---```
public interface IAsyncTaskState
```

Provides access to the state of the asynchronous task.
## Methods

| Method | Description |
| --- | --- |
| [isCanceled()](#isCanceled--) | Gets a value indicating whether the asynchronous task is canceled. |
| [getProgress()](#getProgress--) | Gets the progress of the asynchronous task. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.imaging.progressmanagement.EventType-) | Sets the progress of the asynchronous task. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Increments the progress maximum value. |
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Gets a value indicating whether the asynchronous task is canceled.

Value: `true` if the asynchronous task is canceled; otherwise, `false`.

**Returns:**
boolean - a value indicating whether the asynchronous task is canceled.
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Gets the progress of the asynchronous task.

Value: The progress of the asynchronous task.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the progress of the asynchronous task.
### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.imaging.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Sets the progress of the asynchronous task.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.imaging.progressmanagement/eventtype) | The progress state. |

### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Increments the progress maximum value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The increase value. |

