---
title: EmfPlusRecordType
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione RecordType definisce i tipi di record utilizzati nei metafile EMF.
type: docs
weight: 5030
url: /it/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

L'enumerazione RecordType definisce i tipi di record utilizzati nei metafile EMF+.

```csharp
public enum EmfPlusRecordType : short
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| EmfPlusHeader | `16385` | Questo record specifica l'inizio dei dati EMF+ nel metafile. DEVE essere incorporato nel primo record EMF dopo il[`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) record ([MS-EMF] sezione 2.3.4.2 record). |
| EmfPlusEndOfFile | `16386` | Questo record specifica la fine dei dati EMF+ nel metafile. |
| EmfPlusComment | `16387` | Questo record specifica dati privati arbitrari. |
| EmfPlusGetDC | `16388` | Questo record specifica che i record EMF successivi incontrati nel metafile DOVREBBE essere elaborati. I record EMF cessano di essere elaborati quando viene rilevato il record EMF+ successivo. |
| EmfPlusMultiFormatStart | `16389` | Questo record è riservato e NON DEVE essere utilizzato. |
| EmfPlusMultiFormatSection | `16390` | Questo record è riservato e NON DEVE essere utilizzato. |
| EmfPlusMultiFormatEnd | `16391` | Questo record è riservato e NON DEVE essere utilizzato. |
| EmfPlusObject | `16392` | Questo record specifica un oggetto da utilizzare nelle operazioni grafiche. |
| EmfPlusClear | `16393` | Questo record cancella l'output`spazio delle coordinate` e lo inizializza con un colore di sfondo e una trasparenza specificati. |
| EmfPlusFillRects | `16394` | Questo record definisce come riempire gli interni di una serie di rettangoli, usando un pennello specifico. |
| EmfPlusDrawRects | `16395` | Questo record definisce i tratti della penna per disegnare una serie di rettangoli. |
| EmfPlusFillPolygon | `16396` | Questo record definisce i dati per riempire l'interno di un poligono, usando un pennello specificato. |
| EmfPlusDrawLines | `16397` | Questo record definisce i tratti della penna per disegnare una serie di linee collegate. |
| EmfPlusFillEllipse | `16398` | Questo record definisce come riempire gli interni di un'ellisse, usando un pennello specifico. |
| EmfPlusDrawEllipse | `16399` | Questo record definisce i tratti della penna per disegnare un'ellisse. |
| EmfPlusFillPie | `16400` | Questo record definisce come riempire una sezione di una sezione interna di un'ellisse utilizzando un pennello specificato. |
| EmfPlusDrawPie | `16401` | Questo record definisce i tratti della penna per disegnare una sezione di un'ellisse. |
| EmfPlusDrawArc | `16402` | Il record definisce i tratti di penna per disegnare un arco di ellisse. |
| EmfPlusFillRegion | `16403` | Questo record definisce come riempire l'interno di una regione usando un pennello specifico. |
| EmfPlusFillPath | `16404` | Il record definisce come riempire gli interni delle figure definite in un percorso grafico con un pennello specifico. Un percorso è un oggetto che definisce una sequenza arbitraria di linee, curve e forme. |
| EmfPlusDrawPath | `16405` | Il record definisce i tratti della penna per disegnare le figure in un percorso grafico. Un percorso è un oggetto che definisce una sequenza arbitraria di linee, curve e forme. |
| EmfPlusFillClosedCurve | `16406` | Questo record definisce come riempire l'interno di una spline cardinale chiusa utilizzando un pennello specificato. |
| EmfPlusDrawClosedCurve | `16407` | Questo record definisce la penna e i tratti per disegnare una spline cardinale chiusa. |
| EmfPlusDrawCurve | `16408` | Questo record definisce i tratti della penna per disegnare una spline cardinale. |
| EmfPlusDrawBeziers | `16409` | Questo record definisce i tratti della penna per disegnare una spline di Bezier. |
| EmfPlusDrawImage | `16410` | Questo record definisce un valore in scala[`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)oggetto (sezione 2.2.1.4). Un'immagine può essere costituita da dati bitmap o metafile. |
| EmfPlusDrawImagePoints | `16411` | Questo record definisce un oggetto EmfPlusImage in scala all'interno di un parallelogramma. Un'immagine può essere costituita da dati bitmap o metafile. |
| EmfPlusDrawString | `16412` | Questo record definisce una stringa di testo basata su un font, un rettangolo di layout e un formato. |
| EmfPlusSetRenderingOrigin | `16413` | Questo record definisce l'origine del rendering alle coordinate orizzontali e verticali specificate. Questo vale per i pennelli di tratteggio e per i modelli di dithering a 8 e 16 bit per pixel. |
| EmfPlusSetAntiAliasMode | `16414` | Questo record definisce se abilitare o disabilitare l'anti-alias del testo. L'anti-alias del testo è un metodo per rendere più uniformi le linee e i bordi dei glifi dei caratteri quando vengono disegnati su una superficie di output. |
| EmfPlusSetTextRenderingHint | `16415` | Questo record definisce il processo utilizzato per il rendering del testo. |
| EmfPlusSetTextContrast | `16416` | Questo record imposta il contrasto del testo in base al valore gamma del testo specificato. |
| EmfPlusSetInterpolationMode | `16417` | Questo record definisce la modalità di interpolazione di un oggetto in base al tipo di filtraggio delle immagini specificato. La modalità di interpolazione influenza il modo in cui viene eseguito il ridimensionamento (stiramento e contrazione). |
| EmfPlusSetPixelOffsetMode | `16418` | Questo record definisce la modalità di offset pixel in base al valore di centratura pixel specificato. |
| EmfPlusSetCompositingMode | `16419` | Questo record definisce la modalità di composizione in base allo stato della fusione alfa, che specifica come i colori di origine vengono combinati con i colori di sfondo. |
| EmfPlusSetCompositingQuality | `16420` | Questo record definisce la qualità del compositing, che descrive il livello di qualità desiderato per la creazione di immagini composite da più oggetti. |
| EmfPlusSave | `16421` | Questo record salva lo stato grafico, identificato da un indice specificato, su una pila di stati grafici salvati. Ogni indice dello stack è associato a un particolare stato salvato e l'indice è utilizzato da un[`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) record (sezione 2.3.7.4) per ripristinare lo stato. |
| EmfPlusRestore | `16422` | Questo record ripristina lo stato grafico, identificato da un indice specificato, da uno stack di stati grafici salvati. Ogni indice dello stack è associato a un particolare stato salvato e l'indice è definito da un[`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave) record (sezione 2.3.7.5) per salvare lo stato. |
| EmfPlusBeginContainer | `16423` | Questo record apre un nuovo contenitore di stato grafico e specifica una trasformazione per esso. I contenitori grafici vengono utilizzati per conservare gli elementi dello stato grafico. |
| EmfPlusBeginContainerNoParams | `16424` | Questo record apre un nuovo contenitore dello stato grafico. |
| EmfPlusEndContainer | `16425` | Questo record chiude un contenitore dello stato grafico che era stato precedentemente aperto da un'operazione di inizio contenitore. |
| EmfPlusSetWorldTransform | `16426` | Questo record definisce la trasformazione dello spazio mondiale corrente nel device_context di riproduzione, secondo una matrice di trasformazione specificata. |
| EmfPlusResetWorldTransform | `16427` | Questo record reimposta la trasformazione dello spazio mondiale corrente sulla matrice di identificazione. |
| EmfPlusMultiplyWorldTransform | `16428` | Questo record moltiplica lo spazio mondiale corrente per una matrice di trasformazione specificata. |
| EmfPlusTranslateWorldTransform | `16429` | Questo record applica una trasformazione di traslazione allo spazio mondiale corrente in base alle distanze orizzontali e verticali specificate. |
| EmfPlusScaleWorldTransform | `16430` | Questo record applica una trasformazione di ridimensionamento allo spazio mondiale corrente in base a fattori di scala orizzontali e verticali specificati. |
| EmfPlusRotateWorldTransform | `16431` | Questo record ruota lo spazio mondiale corrente di un angolo specificato. |
| EmfPlusSetPageTransform | `16432` | Questo record specifica fattori di ridimensionamento aggiuntivi per l'attuale trasformazione dello spazio mondiale. |
| EmfPlusResetClip | `16433` | Questo record reimposta la regione di ritaglio corrente per lo spazio mondiale su infinito. |
| EmfPlusSetClipRect | `16434` | Questo record combina l'area di ritaglio corrente con un rettangolo. |
| EmfPlusSetClipPath | `16435` | Questo record combina l'area di ritaglio corrente con un percorso grafico. |
| EmfPlusSetClipRegion | `16436` | Questo record combina l'area di ritaglio corrente con un'altra area grafica. |
| EmfPlusOffsetClip | `16437` | Questo record applica una trasformazione di traslazione all'area di ritaglio corrente dello spazio mondiale. |
| EmfPlusDrawDriverString | `16438` | Questo record specifica l'output di testo con le posizioni dei caratteri. |
| EmfPlusStrokeFillPath | `16439` | Questo record chiude tutte le figure aperte in un tracciato, traccia il contorno del tracciato usando la penna corrente e ne riempie l'interno usando il pennello corrente. |
| EmfPlusSerializableObject | `16440` | Questo record definisce un blocco di parametri degli effetti immagine che è stato serializzato in un buffer di dati. |
| EmfPlusSetTSGraphics | `16441` | Questo record specifica lo stato di un contesto di dispositivo grafico per un server terminal. |
| EmfPlusSetTSClip | `16442` | Questo record specifica le aree di ritaglio nel contesto del dispositivo grafico per un server terminal. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
