---
title: PointData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta i dati del punto Una matrice di punti di conteggio che specificano i punti di inizio fine e controllo delle curve di Bezier. La coordinata finale di una curva di Bezier è la coordinata iniziale della successiva. I punti di controllo vengono utilizzati per produrre leffetto Bezier. Il tipo di dati in questo array è specificato dal campo Flag come segue Tipo di dati Significato Oggetto EmfPlusPointR sezione 2.2.2.37 Se il flag P è impostato nei Flag  i punti specificano le posizioni relative. Oggetto EmfPlusPointF sezione 2.2.2.36 Se i bit P e C sono liberi nel campo Flag i punti specificano le posizioni assolute. Oggetto EmfPlusPoint sezione 2.2.2.35 Se il bit P è azzerato e il bit C è impostato nel campo Flag i punti specificano le posizioni relative. Una curva di Bezier non passa attraverso i suoi punti di controllo. I punti di controllo agiscono come
type: docs
weight: 40
url: /it/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/
---
## EmfPlusDrawBeziers.PointData property

Ottiene o imposta i dati del punto Una matrice di punti di conteggio che specificano i punti di inizio, fine e controllo delle curve di Bezier. La coordinata finale di una curva di Bezier è la coordinata iniziale della successiva. I punti di controllo vengono utilizzati per produrre l'effetto Bezier. Il tipo di dati in questo array è specificato dal campo Flag, come segue: Tipo di dati Significato Oggetto EmfPlusPointR (sezione 2.2.2.37) Se il flag P è impostato nei Flag , i punti specificano le posizioni relative. Oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono liberi nel campo Flag, i punti specificano le posizioni assolute. Oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è azzerato e il bit C è impostato nel campo Flag, i punti specificano le posizioni relative. Una curva di Bezier non passa attraverso i suoi punti di controllo. I punti di controllo agiscono come

```csharp
public PointF[] PointData { get; set; }
```

### Guarda anche

* struct [PointF](../../../aspose.imaging/pointf)
* class [EmfPlusDrawBeziers](../../emfplusdrawbeziers)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawbeziers)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
