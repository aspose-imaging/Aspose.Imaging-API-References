---
title: Relative
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta un valore che indica se questoEmfPlusFillClosedCurveaspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è rispetto alla posizione specificata dallelemento precedente nellarray. Nel caso del primo elemento in PointData si assume una posizione precedente alle coordinate 00. Se azzerato PointData specifica posizioni assolute in base al flag C. Nota Se questo flag è impostato il flag C sopra non è definito e DEVE essere ignorato.
type: docs
weight: 60
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative/
---
## EmfPlusFillClosedCurve.Relative property

Ottiene o imposta un valore che indica se questo[`EmfPlusFillClosedCurve`](../../emfplusfillclosedcurve) è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è rispetto alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se azzerato, PointData specifica posizioni assolute in base al flag C. Nota Se questo flag è impostato, il flag C (sopra) non è definito e DEVE essere ignorato.

```csharp
public bool Relative { get; set; }
```

### Valore della proprietà

`VERO` se relativo; altrimenti,`falso` .

### Guarda anche

* class [EmfPlusFillClosedCurve](../../emfplusfillclosedcurve)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusfillclosedcurve)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->