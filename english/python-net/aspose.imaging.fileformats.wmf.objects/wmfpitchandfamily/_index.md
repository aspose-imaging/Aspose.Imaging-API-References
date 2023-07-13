---
title: WmfPitchAndFamily Class
type: docs
weight: 480
url: /python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---

The PitchAndFamily object specifies the pitch and family properties of a<br/>                Font object (section 2.2.1.2). Pitch refers to the width of the<br/>                characters, and family refers to the general appearance of a font.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily

**Aspose.Imaging Version:** 23.6

The WmfPitchAndFamily type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [WmfPitchAndFamily(byte_data)](#WmfPitchAndFamily_byte_data_0) | Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct. |
| [WmfPitchAndFamily(pitch, family)](#WmfPitchAndFamily_pitch_family_1) | Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct. |
| [WmfPitchAndFamily()](#WmfPitchAndFamily__2) | Initializes a new instance of the WmfPitchAndFamily class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | r | Gets A property of a font that describes its general appearance.<br/>                This MUST be a value in the FamilyFont enumeration |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | r | Gets A property of a font that describes the pitch, of the<br/>                characters. This MUST be a value in the PitchFont enumeration. |
| byte_data | byte | r/w | Sets the <see langword="byte" /> data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_byte()](#to_byte__3) | To the byte. |

### WmfPitchAndFamily(byte_data) {#WmfPitchAndFamily_byte_data_0}


```
 WmfPitchAndFamily(byte_data) 
```

Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| byte_data | byte | The <see langword="byte" /> data. |

### WmfPitchAndFamily(pitch, family) {#WmfPitchAndFamily_pitch_family_1}


```
 WmfPitchAndFamily(pitch, family) 
```

Initializes a new instance of the [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | The pitch. |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | The family. |

### WmfPitchAndFamily() {#WmfPitchAndFamily__2}


```
 WmfPitchAndFamily() 
```

Initializes a new instance of the WmfPitchAndFamily class

### to_byte() {#to_byte__3}


```
 to_byte() 
```

To the byte.

**Returns**

| Type | Description |
| :- | :- |
| byte | The byte value. |


