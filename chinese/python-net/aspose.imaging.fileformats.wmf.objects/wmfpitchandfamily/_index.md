---
title: "WmfPitchAndFamily 类"
type: docs
weight: 480
url: /zh/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---

**Summary:** The PitchAndFamily object specifies the pitch and family properties of a<br/>                Font object (section 2.2.1.2). Pitch refers to the width of the<br/>                characters, and family refers to the general appearance of a font.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily__1) | 初始化 WmfPitchAndFamily 类的新实例 |
| [WmfPitchAndFamily(byte_data)](#WmfPitchAndFamily_byte_data_2) | 初始化 [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>
            结构体的新实例。 |
| [WmfPitchAndFamily(pitch, family)](#WmfPitchAndFamily_pitch_family_3) | 初始化 [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>
            结构体的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| byte_data | System.Byte | r/w | 设置 **byte** 数据。 |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | r | 获取描述字体整体外观的属性。<br/>
                该值必须是 FamilyFont 枚举中的一个值。 |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | r | 获取描述字体音高的属性，关于<br/>
                字符。该值必须是 PitchFont 枚举中的一个值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [to_byte()](#to_byte__1) | 到字节。 |


### Constructor: WmfPitchAndFamily() {#WmfPitchAndFamily__1}


```
 WmfPitchAndFamily() 
```

初始化 WmfPitchAndFamily 类的新实例

### Constructor: WmfPitchAndFamily(byte_data) {#WmfPitchAndFamily_byte_data_2}


```
 WmfPitchAndFamily(byte_data) 
```

初始化 [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>
            结构体的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| byte_data | System.Byte | 该 **byte** 数据。 |

### Constructor: WmfPitchAndFamily(pitch, family) {#WmfPitchAndFamily_pitch_family_3}


```
 WmfPitchAndFamily(pitch, family) 
```

初始化 [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>
            结构体的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | 该音高。 |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | 该族。 |

### Method: to_byte() {#to_byte__1}


```
 to_byte() 
```

到字节。

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 该字节值。 |


