---
title: "WmfMapMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "映射模式"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMapMode extends System.Enum
```

映射模式
## 字段

| 字段 | 描述 |
| --- | --- |
| [Text](#Text) | 文本：每个逻辑单元映射到一个设备像素。 |
| [Lometric](#Lometric) | 该 lometric 每个逻辑单元映射到 0.1 毫米。 |
| [Himetric](#Himetric) | 该 himetric 每个逻辑单元映射到 0.01 毫米。 |
| [Loenglish](#Loenglish) | 该 loenglish 每个逻辑单元映射到 0.01 英寸。 |
| [Hienglish](#Hienglish) | 该 hienglish 每个逻辑单元映射到 0.001 英寸。 |
| [Twips](#Twips) | 该 twips 每个逻辑单元映射到一个点的二十分之一 (1/20)。 |
| [Isotropic](#Isotropic) | 该 isotropic 逻辑单元映射到任意设备单元，且轴等比例缩放；也就是说，x 轴上的一个单位等于 y 轴上的一个单位。 |
| [Anisotropic](#Anisotropic) | 该 anisotropic 逻辑单元映射到任意单元，且轴按任意比例缩放。 |
### Text {#Text}
```
public static final short Text
```


该 text 每个逻辑单元映射到一个设备像素。正 x 向右；正 y 向下

### Lometric {#Lometric}
```
public static final short Lometric
```


该 lometric 每个逻辑单元映射到 0.1 毫米。正 x 向右；正 y 向上。

### Himetric {#Himetric}
```
public static final short Himetric
```


该 himetric 每个逻辑单元映射到 0.01 毫米。正 x 向右；正 y 向上。

### Loenglish {#Loenglish}
```
public static final short Loenglish
```


该 loenglish 每个逻辑单元映射到 0.01 英寸。正 x 向右；正 y 向上。

### Hienglish {#Hienglish}
```
public static final short Hienglish
```


该 hienglish 每个逻辑单元映射到 0.001 英寸。正 x 向右；正 y 向上。

### Twips {#Twips}
```
public static final short Twips
```


该 twips 每个逻辑单元映射到一个点的二十分之一 (1/20)。在印刷中，一个点等于 1/72 英寸；因此，1/20 点等于 1/1440 英寸。此单位也称为 "twip"。

### Isotropic {#Isotropic}
```
public static final short Isotropic
```


该 isotropic 逻辑单元映射到任意设备单元，且轴等比例缩放；也就是说，x 轴上的一个单位等于 y 轴上的一个单位。META\_SETWINDOWEXT 和 META\_SETVIEWPORTEXT 记录指定了单位和轴的方向。

### Anisotropic {#Anisotropic}
```
public static final short Anisotropic
```


该 anisotropic 逻辑单元映射到任意单元，且轴按任意比例缩放。

