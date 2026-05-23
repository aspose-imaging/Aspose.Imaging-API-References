---
title: "EmfUniversalFontId-klass"
type: docs
weight: 280
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | Initierar en ny instans av EmfUniversalFontId-klass |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| kontrollsumma | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som är kontrollsumman för teckensnittet.<br/>            Kontrollsummavärdet har följande betydelser.<br/>            0x00000000  Objektet är ett enhetsteckensnitt. <br/>            0x00000001  Objektet är ett Type 1-teckensnitt som har installerats på klientmaskinen och är <br/>            uppräkning av PostScript-skrivardrivrutinen som ett enhetsteckensnitt. <br/>            0x00000002  Objektet är inte ett teckensnitt utan ett Type 1-rasteriseringsprogram. <br/>            3 ≤ värde   Objektet är en bitmap, vektor eller TrueType-teckensnitt, eller ett Type 1-rasteriserat teckensnitt som <br/>            skapades av ett Type 1-rasteriseringsprogram. |
| index | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som är ett index associerat med teckensnittobjektet. <br/>            Betydelsen av detta fält bestäms av teckensnittstypen. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

Initierar en ny instans av EmfUniversalFontId-klass

