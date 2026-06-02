---
title: "EmfPlusPathPointFlags Enumeration"
type: docs
weight: 290
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

一个 32 位无符号整数，用于指定如何解释此对象定义的点及其关联的点类型。<br/>            C (1 位)：如果设置，则 PathPoints 数组使用 16 位整数坐标指定坐标空间中的绝对位置。<br/>            如果未设置，则 PathPoints 数组使用 32 位浮点坐标指定坐标空间中的绝对位置。<br/>            注意，如果下面的 P 标志被设置，则此标志可能未设置且必须被忽略。<br/>            R (1 位)：如果设置，PathPointTypes 数组中的点类型由 EmfPlusPathPointTypeRle 对象（第 2.2.2.32 节）指定，<br/>            这些对象使用行程长度编码 (RLE) 压缩，和/或由 EmfPlusPathPointType 对象（第 2.2.2.31 节）指定。有关 RLE 压缩的更多信息，请参阅 [MS-WMF] 第 3.1.6 节。<br/>            如果未设置，则 PathPointTypes 数组中的点类型由 EmfPlusPathPointType 对象指定。<br/>            P (1 位)：如果设置，PathPoints 数组中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PathPoints 的第一个元素，假定前一个位置为坐标 (0,0)。<br/>            如果未设置，PathPoints 数组中的每个元素指定绝对位置。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| C | c 标志 |
| P | p 标志 |
| R | r 标志 |
