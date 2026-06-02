---
title: "EmfColorAdjustment klass"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | Initierar en ny instans av EmfColorAdjustment-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n:te potensvärde för den <br/>            blå primärfärgen i källfärgerna. Detta värde SKA ligga i intervallet från 2 500 till 65 000. <br/>            Ett värde på 10 000 betyder att gamma‑korrektion INTE SKA utföras. |
| ljusstyrka | int | r/w | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden ljusstyrka som ska tillämpas på källobjektet. <br/>            Detta värde SKA ligga i intervallet från –100 till 100.<br/>            Ett värde på noll betyder att ljusstyrkejustering INTE SKA utföras. |
| colorfullness | int | r/w | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden färgrikedom som ska tillämpas på källobjektet. <br/>            Detta värde SKA ligga i intervallet från –100 till 100. <br/>            Ett värde på noll betyder att färgrikedomjustering INTE SKA utföras |
| kontrast | int | r/w | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden kontrast som ska tillämpas på källobjektet. <br/>            Detta värde SKA ligga i intervallet från –100 till 100. Ett värde på noll betyder att kontrastjustering INTE SKA utföras. |
| green_gamma | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n:te potensvärde för den gröna <br/>            primärfärgen i källfärgerna. Detta värde SKA ligga i intervallet från 2 500 till 65 000. <br/>            Ett värde på 10 000 betyder att gamma‑korrektion INTE SKA utföras. |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar typen av standardljuskälla som bilden visas under, från Illuminant‑enumerationen (avsnitt 2.1.19). |
| red_gamma | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar gamma‑korrektionens n:te potensvärde för den röda <br/>            primärfärgen i källfärgerna. Detta värde SKA ligga i intervallet från 2 500 till 65 000.<br/>            Ett värde på 10 000 betyder att gamma‑korrektion INTE SKA utföras. |
| red_green_tint | int | r/w | Hämtar eller anger ett 16-bitars signerat heltal som specificerar mängden röd eller grön nyansjustering som ska tillämpas <br/>            på källobjektet. Detta värde SKA ligga i intervallet från –100 till 100. <br/>            Positiva tal justerar mot rött och negativa tal justerar mot grönt. <br/>            Ett värde på noll betyder att nyansjustering INTE SKA utföras |
| reference_black | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar den svarta referensen för källfärgerna. <br/>            Alla färger som är mörkare än detta behandlas som svarta. <br/>            Detta värde SKA ligga i intervallet från noll till 4 000 |
| reference_white | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar den vita referensen för källfärgerna. <br/>            Alla färger som är ljusare än detta behandlas som vita. <br/>            Detta värde SKA ligga i intervallet från 6 000 till 10 000. |
| storlek | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar storleken i byte för detta objekt. Detta MÅSTE vara 0x0018. |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som specificerar hur utdata bilden ska förberedas. Detta fält kan <br/>            sättas till NULL eller till någon kombination av värden i ColorAdjustment‑enumerationen (avsnitt 2.1.5). |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

Initierar en ny instans av EmfColorAdjustment-klassen

