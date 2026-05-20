---
title: "WmfMapMode"
second_title: "Aspose.Imaging for Java API 参考文档"
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
| [Text](#Text) | 文本：每个逻辑单位映射到一个设备像素。 |
| [Lometric](#Lometric) | lometric：每个逻辑单位映射到 0.1 毫米。 |
| [Himetric](#Himetric) | himetric：每个逻辑单位映射到 0.01 毫米。 |
| [Loenglish](#Loenglish) | loenglish：每个逻辑单位映射到 0.01 英寸。 |
| [Hienglish](#Hienglish) | hienglish：每个逻辑单位映射到 0.001 英寸。 |
| [Twips](#Twips) | twips：每个逻辑单位映射到一点的二十分之一 (1/20)。 |
| [Isotropic](#Isotropic) | isotropic：逻辑单位映射到任意设备单位，且轴的比例相等；即 x 轴上的一个单位等于 y 轴上的一个单位。 |
| [Anisotropic](#Anisotropic) | anisotropic：逻辑单位映射到任意单位，轴的比例任意。 |
### Text {#Text}
```
public static final short Text
```


文本：每个逻辑单位映射到一个设备像素。正向 x 向右；正向 y 向下。

### Lometric {#Lometric}
```
public static final short Lometric
```


lometric：每个逻辑单元映射为 0.1 毫米。正 x 向右；正 y 向上。

### Himetric {#Himetric}
```
public static final short Himetric
```


himetric：每个逻辑单元映射为 0.01 毫米。正 x 向右；正 y 向上。

### Loenglish {#Loenglish}
```
public static final short Loenglish
```


loenglish：每个逻辑单元映射为 0.01 英寸。正 x 向右；正 y 向上。

### Hienglish {#Hienglish}
```
public static final short Hienglish
```


hienglish：每个逻辑单元映射为 0.001 英寸。正 x 向右；正 y 向上。

### Twips {#Twips}
```
public static final short Twips
```


twips：每个逻辑单元映射为一点的二十分之一 (1/20)。在印刷中，点等于 1/72 英寸；因此，1/20 点等于 1/1440 英寸。此单位也称为 “twip”。

### Isotropic {#Isotropic}
```
public static final short Isotropic
```


isotropic：逻辑单元映射为任意设备单元，且轴等比例缩放；即 x 轴上的一个单位等于 y 轴上的一个单位。META\_SETWINDOWEXT 和 META\_SETVIEWPORTEXT 记录指定单位和轴的方向。

### Anisotropic {#Anisotropic}
```
public static final short Anisotropic
```


anisotropic：逻辑单位映射到任意单位，轴的比例任意。

