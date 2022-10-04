---
title: EmfPlusGraphicsVersion
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto EmfPlusGraphicsVersion specifica la versione della grafica del sistema operativo utilizzata per creare un metafile EMF .
type: docs
weight: 5470
url: /it/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
## EmfPlusGraphicsVersion class

L'oggetto EmfPlusGraphicsVersion specifica la versione della grafica del sistema operativo utilizzata per creare un metafile EMF+ .

```csharp
public sealed class EmfPlusGraphicsVersion : EmfPlusStructureObjectType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusGraphicsVersion](emfplusgraphicsversion)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GraphicsVersion](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/graphicsversion) { get; set; } | Ottiene una GraphicsVersion (12 bit): la versione della grafica del sistema operativo. Questo valore DEVE essere definito in [`EmfPlusGraphicsVersion`](../emfplusgraphicsversion) enumerazione |
| [MetafileSignature](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/metafilesignature) { get; set; } | Ottiene un MetafileSignature (20 bit): un valore che identifica il tipo di metafile. Il valore per un metafile EMF+ è 0xDBC01. |

### Osservazioni

Le versioni grafiche sono estensibili dal fornitore; tuttavia, per garantire l'interoperabilità, qualsiasi estensione di questo tipo DEVE essere implementata sia nei client che nei server di metafile EMF+.

### Guarda anche

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->