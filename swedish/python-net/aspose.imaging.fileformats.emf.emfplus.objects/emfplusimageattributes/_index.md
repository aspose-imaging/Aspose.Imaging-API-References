---
title: "EmfPlusImageAttributes-klass"
type: docs
weight: 390
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | Initierar en ny instans av EmfPlusImageAttributes-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | Hämtar eller anger EmfPlusARGB-objektet (avsnitt 2.2.2.1) som specificerar kantfärgen att använda <br/>            när WrapMode-värdet är WrapModeClamp. Denna färg är synlig när <br/>            källrektangeln som bearbetas av en EmfPlusDrawImage (avsnitt 2.3.4.8)-post<br/>            är större än själva bilden. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar objektets klämningsbeteende.<br/>            Det används inte förrän detta objekt appliceras på en bild som <br/>            ritas. Detta värde MÅSTE vara ett av värdena som definieras i <br/>            följande tabell. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Hämtar eller anger versionen. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur kantförhållanden hanteras med <br/>            ett värde från WrapMode‑enumerationen (avsnitt 2.1.1.34). |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

Initierar en ny instans av EmfPlusImageAttributes-klassen

