---
title: PointData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta il punto data Una matrice di punti Conteggio che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa la curva continua attraverso lultimo punto nellarray PointData e si collega al primo punto nellarray. Il tipo di dati in questo array è specificato dal campo Flags come segue Tipo di dati Significato EmfPlusPointR oggetto sezione 2.2.2.37 Se il flag P è impostato nei Flag i punti specificano le posizioni relative. Oggetto EmfPlusPointF sezione 2.2.2.36 Se i bit P e C sono impostati nel campo Flag i punti specificano posizioni assolute. Oggetto EmfPlusPoint sezione 2.2.2.35 Se il bit P è azzerato e il bit C è impostato nel campo Flag i punti specificano le posizioni relative.
type: docs
weight: 40
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/
---
## EmfPlusDrawClosedCurve.PointData property

Ottiene o imposta il punto data Una matrice di punti Conteggio che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto nell'array PointData e si collega al primo punto nell'array. Il tipo di dati in questo array è specificato dal campo Flags, come segue: Tipo di dati Significato EmfPlusPointR oggetto (sezione 2.2.2.37) Se il flag P è impostato nei Flag, i punti specificano le posizioni relative. Oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono impostati nel campo Flag, i punti specificano posizioni assolute. Oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è azzerato e il bit C è impostato nel campo Flag, i punti specificano le posizioni relative.

```csharp
public PointF[] PointData { get; set; }
```

### Guarda anche

* struct [PointF](../../../aspose.imaging/pointf)
* class [EmfPlusDrawClosedCurve](../../emfplusdrawclosedcurve)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawclosedcurve)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
