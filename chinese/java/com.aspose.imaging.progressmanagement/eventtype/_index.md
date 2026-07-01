---
title: "EventType"
second_title: "Aspose.Imaging for Java API 参考"
description: "此枚举描述图像处理操作期间可能发生的进度事件类型。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

此枚举描述图像处理操作期间可能发生的进度事件类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | 操作处理当前阶段的相对进度 |
| [StageChange](#StageChange) | 操作的下一阶段已启动 |
| [Initialization](#Initialization) | 操作的初始化 |
| [PreProcessing](#PreProcessing) | 预处理 |
| [Processing](#Processing) | 处理 |
| [Finalization](#Finalization) | 操作的完成 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


操作处理当前阶段的相对进度

### StageChange {#StageChange}
```
public static final EventType StageChange
```


操作的下一阶段已启动

### Initialization {#Initialization}
```
public static final EventType Initialization
```


操作的初始化

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


预处理

### Processing {#Processing}
```
public static final EventType Processing
```


处理

### Finalization {#Finalization}
```
public static final EventType Finalization
```


操作的完成

### values() {#values--}
```
public static EventType[] values()
```




**Returns:**
com.aspose.imaging.progressmanagement.EventType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static EventType valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
