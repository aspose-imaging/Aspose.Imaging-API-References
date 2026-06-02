---
title: "WmfClipPrecisionFlags 枚举"
type: docs
weight: 50
url: /zh/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

ClipPrecision 标志指定剪裁精度，定义如何剪裁部分位于剪裁区域外的字符<br/>                。这些标志可以组合以指定多个选项。

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| 字符 | 此值不应使用。 |
| 默认 | 指定必须使用默认裁剪。 |
| DFA_DISABLE | 此值指定应关闭字体关联[35]。<br/>                [35] 此值在 Windows 95、Windows 98 和 Windows Millennium Edition 中不受支持。<br/>                字体关联在 Windows 2000、Windows XP 和 Windows Server 2003 中已关闭。<br/>                此值在以下 Windows 版本中被忽略：<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
| 嵌入 | 此值指定在渲染文档<br/>                内容时必须使用字体嵌入；嵌入的字体为只读。 |
| LH_ANGLES | 此值用于控制字体旋转，规则如下：<br/>                - 如果设置，则所有字体的旋转应由坐标系的方向决定；即方向是左手坐标系还是右手坐标系。<br/>                - 如果未设置，设备字体应逆时针旋转，但其他字体的旋转应由坐标系的方向决定。 |
| 笔画 | 在枚举栅格化、TrueType 和<br/>                矢量字体时可能返回此值。<br/>                [33]（Windows NT 3.1、Windows NT 3.5、Windows NT 3.51、Windows NT 4.0、<br/>                Windows 2000 和 Windows XP：枚举字体时始终返回此值。） |
| TT_ALWAYS | 此值不应使用[34]。<br/>                [34] 此值在以下 Windows 版本中被忽略：<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
