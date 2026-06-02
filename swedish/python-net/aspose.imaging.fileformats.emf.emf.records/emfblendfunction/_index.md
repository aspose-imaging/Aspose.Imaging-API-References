---
title: "EmfBlendFunction klass"
type: docs
weight: 90
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | Initierar en ny instans av EmfBlendFunction klass |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | Initierar en ny instans av klassen [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | Hämtar en struktur som specificerar hur käll- och destinationspixlar <br/>            tolkas med avseende på alfa‑transparens. |
| blend_flags | System.Byte | r | Hämtar blandningsflaggorna.<br/>            Detta värde MÅSTE vara 0x00 och MÅSTE ignoreras. |
| blend_operation | System.Byte | r | Hämtar koden för blandningsoperationen. <br/>            Den enda källa- och destinations<br/>            blandningsoperation som har definierats är 0x00, vilket anger att källbitmapen<br/>            MÅSTE kombineras med destinationsbitmapen baserat på alfa‑transparentvärdena<br/>            för källpixelarna. Se följande ekvationer för detaljer. |
| src_constant_alpha | System.Byte | r | Hämtar ett 8-bitars osignerat heltal som specificerar alfa‑transparens, <br/>            vilket bestämmer blandningen av källa‑ och destinationsbitmapar. Detta värde MÅSTE vara <br/>            använt på hela källbitmapen. Det minsta alfa‑transparentvärdet, noll, <br/>            motsvarar helt genomskinligt och det maximala värdet, 0xFF, motsvarar <br/>            helt ogenomskinligt. I praktiken anger ett värde på 0xFF att per‑pixel‑alfa‑värdena <br/>            bestämmer blandningen av källa‑ och destinationsbitmapar. Se ekvationerna senare i <br/>            detta avsnitt för detaljer. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_int()](#to_int__1) | Konverterar strängrepresentationen av ett tal till ett heltal. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

Initierar en ny instans av EmfBlendFunction klass

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

Initierar en ny instans av klassen [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dword_data | int | DWORD‑data. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Konverterar strängrepresentationen av ett tal till ett heltal.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | DWORD‑värdet för strukturen. |


