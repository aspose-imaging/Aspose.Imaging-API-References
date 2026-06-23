---
title: "WmfBinaryRasterOperation"
second_title: "Aspose.Imaging for Java API 参考"
description: "BinaryRasterOperation 枚举部分列出了二进制光栅操作代码。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

BinaryRasterOperation 枚举部分列出了二进制光栅操作代码。光栅操作代码定义了元文件处理如何将选定笔的位与目标位图的位组合。

--------------------

每个光栅操作代码表示一种布尔运算，其中选定笔和目标位图的像素值被组合。以下是这些运算中使用的两个操作数。操作数 含义 P 选定的笔 D 目标位图 a 按位与 n 按位非（取反） o 按位或 x 按位异或 (XOR)
## 字段

| 字段 | 描述 |
| --- | --- |
| [Black](#Black) | 0，像素始终为 0。 |
| [Notmergepen](#Notmergepen) | DPon，像素是 MERGEPEN 颜色的反相。 |
| [Masknotpen](#Masknotpen) | DPna，像素是屏幕颜色与笔颜色的反相的组合。 |
| [Notcopypen](#Notcopypen) | Pn，像素是笔颜色的反相。 |
| [Maskpennot](#Maskpennot) | PDna，像素是笔颜色和屏幕颜色的反相共同拥有的颜色的组合。 |
| [Not](#Not) | Dn，像素是屏幕颜色的反相。 |
| [Xorpen](#Xorpen) | DPx，像素是笔颜色或屏幕颜色中的颜色组合，但不同时包含两者。 |
| [Notmaskpen](#Notmaskpen) | DPan，像素是MASKPEN颜色的反相。 |
| [Maskpen](#Maskpen) | DPa，像素是笔颜色和屏幕颜色共同拥有的颜色的组合。 |
| [Notxorpen](#Notxorpen) | DPxn，像素是XORPEN颜色的反相。 |
| [Nop](#Nop) | D，像素保持不变。 |
| [Mergenotpen](#Mergenotpen) | DPno，像素是屏幕颜色和笔颜色的反相共同拥有的颜色的组合。 |
| [Copypen](#Copypen) | P，像素是笔颜色。 |
| [Mergepennot](#Mergepennot) | PDno，像素是笔颜色与屏幕颜色的反相的组合。 |
| [Mergepen](#Mergepen) | DPo，像素是笔颜色与屏幕颜色的组合。 |
| [White](#White) | 1，像素始终为1 |
### Black {#Black}
```
public static final int Black
```


0，像素始终为 0。

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon，像素是 MERGEPEN 颜色的反相。

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna，像素是屏幕颜色与笔颜色的反相的组合。

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn，像素是笔颜色的反相。

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna，像素是笔颜色和屏幕颜色的反相共同拥有的颜色的组合。

### Not {#Not}
```
public static final int Not
```


Dn，像素是屏幕颜色的反相。

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx，像素是笔颜色或屏幕颜色中的颜色组合，但不同时包含两者。

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan，像素是MASKPEN颜色的反相。

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa，像素是笔颜色和屏幕颜色共同拥有的颜色的组合。

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn，像素是XORPEN颜色的反相。

### Nop {#Nop}
```
public static final int Nop
```


D，像素保持不变。

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno，像素是屏幕颜色和笔颜色的反相共同拥有的颜色的组合。

### Copypen {#Copypen}
```
public static final int Copypen
```


P，像素是笔颜色。

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno，像素是笔颜色与屏幕颜色的反相的组合。

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo，像素是笔颜色与屏幕颜色的组合。

### White {#White}
```
public static final int White
```


1，像素始终为1

