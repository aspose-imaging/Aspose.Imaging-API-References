---
title: WmfPitchAndFamily Class
type: docs
weight: 480
url: /python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---

**Summary:** The PitchAndFamily object specifies the pitch and family properties of a<br/>                Font object (section 2.2.1.2). Pitch refers to the width of the<br/>                characters, and family refers to the general appearance of a font.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily__1) | Initializes a new instance of the WmfPitchAndFamily class |
| [WmfPitchAndFamily(byte_data)](#WmfPitchAndFamily_byte_data_2) | Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct. |
| [WmfPitchAndFamily(pitch, family)](#WmfPitchAndFamily_pitch_family_3) | Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| byte_data | System.Byte | r/w | Sets the **byte** data. |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | r | Gets A property of a font that describes its general appearance.<br/>                This MUST be a value in the FamilyFont enumeration |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | r | Gets A property of a font that describes the pitch, of the<br/>                characters. This MUST be a value in the PitchFont enumeration. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_byte()](#to_byte__1) | To the byte. |


### Constructor: WmfPitchAndFamily() {#WmfPitchAndFamily__1}


```
 WmfPitchAndFamily() 
```

Initializes a new instance of the WmfPitchAndFamily class

### Constructor: WmfPitchAndFamily(byte_data) {#WmfPitchAndFamily_byte_data_2}


```
 WmfPitchAndFamily(byte_data) 
```

Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| byte_data | System.Byte | The **byte** data. |

### Constructor: WmfPitchAndFamily(pitch, family) {#WmfPitchAndFamily_pitch_family_3}


```
 WmfPitchAndFamily(pitch, family) 
```

Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | The pitch. |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | The family. |

### Method: to_byte() {#to_byte__1}


```
 to_byte() 
```

To the byte.

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The byte value. |


