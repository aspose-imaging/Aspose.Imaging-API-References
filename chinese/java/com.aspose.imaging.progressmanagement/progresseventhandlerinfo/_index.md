---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.Imaging for Java API 参考"
description: "此类表示图像加载/保存/导出操作进度的信息，可在外部应用程序中用于向最终用户显示转换进度"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

此类表示图像加载/保存/导出操作进度的信息，可在外部应用程序中用于向最终用户显示转换进度。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDescription()](#getDescription--) | 获取事件的描述 |
| [getEventType()](#getEventType--) | 获取事件的类型。 |
| [getMaxValue()](#getMaxValue--) | 获取上限进度值。 |
| [getValue()](#getValue--) | 获取当前进度值。 |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// 示例：在加载/导出操作中使用单独的操作进度事件处理程序
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// STDOUT 日志可能如下所示：
//        加载事件 初始化 : 1/4
//        加载事件 预处理 : 2/4
//        加载事件 处理 : 3/4
//        加载事件 完成 : 4/4
//        导出事件 初始化 : 1/4
//        导出事件 预处理 : 2/4
//        导出事件 处理 : 3/4
//        导出事件 相对进度 : 1/1
//        加载事件 相对进度 : 1/1
//        导出事件 完成 : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


获取事件的描述

值：描述。

**Returns:**
java.lang.String - 事件的描述
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


获取事件的类型。

值：事件的类型。

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


获取上限进度值。

值：上限进度值。

**Returns:**
int - 上限进度值。
### getValue() {#getValue--}
```
public final int getValue()
```


获取当前进度值。

值：进度值。

**Returns:**
int - 当前进度值。
