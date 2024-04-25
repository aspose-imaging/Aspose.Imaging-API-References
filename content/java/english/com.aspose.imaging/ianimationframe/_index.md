---
title: IAnimationFrame
second_title: Aspose.Imaging for Java API Reference
description: The Animation frame
type: docs
weight: 124
url: /com.aspose.imaging/ianimationframe/
---```
public interface IAnimationFrame
```

The Animation frame
## Methods

| Method | Description |
| --- | --- |
| [getFrameTime()](#getFrameTime--) | Gets the frame duration. |
| [getFrameTop()](#getFrameTop--) | Gets the frame top offset. |
| [getFrameLeft()](#getFrameLeft--) | Gets the frame left offset. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Gets a value indicating whether [use alpha blending]. |
| [getDisposalMethod()](#getDisposalMethod--) | Gets the disposal method. |
| [getFullFrame()](#getFullFrame--) | Gets the full frame. |
### getFrameTime() {#getFrameTime--}
```
public abstract int getFrameTime()
```


Gets the frame duration.

**Returns:**
int - the frame duration.
### getFrameTop() {#getFrameTop--}
```
public abstract int getFrameTop()
```


Gets the frame top offset.

**Returns:**
int - the frame top offset.
### getFrameLeft() {#getFrameLeft--}
```
public abstract int getFrameLeft()
```


Gets the frame left offset.

**Returns:**
int - the frame left offset.
### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public abstract boolean isUseAlphaBlending()
```


Gets a value indicating whether [use alpha blending].

Value: `true` if [use alpha blending]; otherwise, `false`.

**Returns:**
boolean - a value indicating whether [use alpha blending].
### getDisposalMethod() {#getDisposalMethod--}
```
public abstract int getDisposalMethod()
```


Gets the disposal method.

**Returns:**
int - the disposal method.
### getFullFrame() {#getFullFrame--}
```
public abstract RasterImage getFullFrame()
```


Gets the full frame.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The RasterImage with full frame
