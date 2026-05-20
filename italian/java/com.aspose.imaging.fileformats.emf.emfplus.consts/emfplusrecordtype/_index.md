---
title: "EmfPlusRecordType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione RecordType definisce i tipi di record utilizzati nei metafile EMF."
type: docs
weight: 45
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

L'enumerazione RecordType definisce i tipi di record utilizzati nei metafili EMF+.
## Campi

| Campo | Descrizione |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | Questo record specifica l'inizio dei dati EMF+ nel metafile. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | Questo record specifica la fine dei dati EMF+ nel metafile. |
| [EmfPlusComment](#EmfPlusComment) | Questo record specifica dati privati arbitrari. |
| [EmfPlusGetDC](#EmfPlusGetDC) | Questo record specifica che i successivi record EMF incontrati nel metafile DEVONO essere elaborati. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | Questo record è riservato e NON DEVE essere utilizzato. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | Questo record è riservato e NON DEVE essere utilizzato. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | Questo record è riservato e NON DEVE essere utilizzato. |
| [EmfPlusObject](#EmfPlusObject) | Questo record specifica un oggetto da utilizzare nelle operazioni grafiche. |
| [EmfPlusClear](#EmfPlusClear) | Questo record cancella lo `coordinate space` di output e lo inizializza con un colore di sfondo e trasparenza specificati. |
| [EmfPlusFillRects](#EmfPlusFillRects) | Questo record definisce come riempire gli interni di una serie di rettangoli, utilizzando un pennello specificato. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | Questo record definisce i tratti della penna per disegnare una serie di rettangoli. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | Questo record definisce i dati per riempire l'interno di un poligono, utilizzando un pennello specificato. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | Questo record definisce i tratti della penna per disegnare una serie di linee collegate. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | Questo record definisce come riempire gli interni di un'ellisse, utilizzando un pennello specificato. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | Questo record definisce i tratti della penna per disegnare un'ellisse. |
| [EmfPlusFillPie](#EmfPlusFillPie) | Questo record definisce come riempire una sezione di una sezione interna di un'ellisse usando un pennello specificato. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | Questo record definisce i tratti della penna per disegnare una sezione di un'ellisse. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | Il record definisce i tratti della penna per disegnare un arco di un'ellisse. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | Questo record definisce come riempire l'interno di una regione usando un pennello specificato. |
| [EmfPlusFillPath](#EmfPlusFillPath) | Il record definisce come riempire gli interni delle figure definite in un percorso grafico con un pennello specificato. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | Il record definisce i tratti della penna per disegnare le figure in un percorso grafico. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | Questo record definisce come riempire l'interno di una spline cardinale chiusa usando un pennello specificato. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | Questo record definisce la penna e i tratti per disegnare una spline cardinale chiusa. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | Questo record definisce i tratti della penna per disegnare una spline cardinale. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | Questo record definisce i tratti della penna per disegnare una spline di Bézier. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | Questo record definisce un oggetto [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) scalato (sezione 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | Questo record definisce un oggetto EmfPlusImage scalato all'interno di un parallelogramma. |
| [EmfPlusDrawString](#EmfPlusDrawString) | Questo record definisce una stringa di testo basata su un carattere, un rettangolo di layout e un formato. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | Questo record definisce l'origine del rendering alle coordinate orizzontali e verticali specificate. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | Questo record definisce se abilitare o disabilitare l'antialiasing del testo. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | Questo record definisce il processo utilizzato per il rendering del testo. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | Questo record imposta il contrasto del testo secondo il valore gamma del testo specificato. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | Questo record definisce la modalità di interpolazione di un oggetto secondo il tipo di filtraggio dell'immagine specificato. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | Questo record definisce la modalità di offset dei pixel secondo il valore di centratura dei pixel specificato. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | Questo record definisce la modalità di composizione secondo lo stato del blending alfa, che specifica come i colori di origine vengono combinati con i colori di sfondo. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | Questo record definisce la qualità di composizione, che descrive il livello desiderato di qualità per creare immagini composite da più oggetti. |
| [EmfPlusSave](#EmfPlusSave) | Questo record salva lo stato grafico, identificato da un indice specificato, su una pila di stati grafici salvati. |
| [EmfPlusRestore](#EmfPlusRestore) | Questo record ripristina lo stato grafico, identificato da un indice specificato, da una pila di stati grafici salvati. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | Questo record apre un nuovo contenitore di stato grafico e specifica una trasformazione per esso. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | Questo record apre un nuovo contenitore di stato grafico. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | Questo record chiude un contenitore di stato grafico che era stato precedentemente aperto da un'operazione di avvio del contenitore. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | Questo record definisce la trasformazione dello spazio mondo corrente nel playback device\_context, in base a una matrice di trasformazione specificata. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | Questo record ripristina la trasformazione dello spazio mondo corrente alla matrice identità. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | Questo record moltiplica lo spazio mondo corrente per una matrice di trasformazione specificata. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | Questo record applica una trasformazione di traslazione allo spazio mondo corrente mediante distanze orizzontali e verticali specificate. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | Questo record applica una trasformazione di scala allo spazio mondo corrente mediante fattori di scala orizzontali e verticali specificati. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | Questo record ruota lo spazio mondo corrente di un angolo specificato. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | Questo record specifica fattori di scala aggiuntivi per la trasformazione dello spazio mondo corrente. |
| [EmfPlusResetClip](#EmfPlusResetClip) | Questo record ripristina la regione di ritaglio corrente per lo spazio mondo all'infinito. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | Questo record combina la regione di ritaglio corrente con un rettangolo. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | Questo record combina la regione di ritaglio corrente con un percorso grafico. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | Questo record combina la regione di ritaglio corrente con un'altra regione grafica. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | Questo record applica una trasformazione di traslazione sulla regione di ritaglio corrente dello spazio mondo. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | Questo record specifica l'output di testo con le posizioni dei caratteri. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | Questo record chiude tutte le figure aperte in un percorso, traccia il contorno del percorso usando la penna corrente e riempie il suo interno usando il pennello corrente. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | Questo record definisce un blocco di parametri di effetti immagine che è stato serializzato in un buffer di dati. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | Questo record specifica lo stato di un contesto dispositivo grafico per un server terminale. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | Questo record specifica le aree di ritaglio nel contesto dispositivo grafico per un server terminale. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


Questo record specifica l'inizio dei dati EMF+ nel metafile. Deve essere incorporato nel primo record EMF dopo il record [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) ([MS-EMF] sezione 2.3.4.2 record).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


Questo record specifica la fine dei dati EMF+ nel metafile.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


Questo record specifica dati privati arbitrari.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


Questo record specifica che i record EMF successivi incontrati nel metafile DEVONO essere elaborati. I record EMF cessano di essere elaborati quando viene incontrato il successivo record EMF+.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


Questo record è riservato e NON DEVE essere utilizzato.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


Questo record è riservato e NON DEVE essere utilizzato.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


Questo record è riservato e NON DEVE essere utilizzato.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


Questo record specifica un oggetto da utilizzare nelle operazioni grafiche.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


Questo record cancella lo `coordinate space` di output e lo inizializza con un colore di sfondo e trasparenza specificati.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


Questo record definisce come riempire gli interni di una serie di rettangoli, utilizzando un pennello specificato.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


Questo record definisce i tratti della penna per disegnare una serie di rettangoli.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


Questo record definisce i dati per riempire l'interno di un poligono, utilizzando un pennello specificato.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


Questo record definisce i tratti della penna per disegnare una serie di linee collegate.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


Questo record definisce come riempire gli interni di un'ellisse, utilizzando un pennello specificato.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


Questo record definisce i tratti della penna per disegnare un'ellisse.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


Questo record definisce come riempire una sezione di una sezione interna di un'ellisse usando un pennello specificato.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


Questo record definisce i tratti della penna per disegnare una sezione di un'ellisse.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


Il record definisce i tratti della penna per disegnare un arco di un'ellisse.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


Questo record definisce come riempire l'interno di una regione usando un pennello specificato.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


Il record definisce come riempire gli interni delle figure definite in un percorso grafico con un pennello specificato. Un percorso è un oggetto che definisce una sequenza arbitraria di linee, curve e forme.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


Il record definisce i tratti di penna per disegnare le figure in un percorso grafico. Un percorso è un oggetto che definisce una sequenza arbitraria di linee, curve e forme.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


Questo record definisce come riempire l'interno di una spline cardinale chiusa usando un pennello specificato.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


Questo record definisce la penna e i tratti per disegnare una spline cardinale chiusa.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


Questo record definisce i tratti della penna per disegnare una spline cardinale.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


Questo record definisce i tratti della penna per disegnare una spline di Bézier.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


Questo record definisce un oggetto [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) scalato (sezione 2.2.1.4). Un'immagine può consistere in dati bitmap o metafile.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


Questo record definisce un oggetto EmfPlusImage scalato all'interno di un parallelogramma. Un'immagine può consistere in dati bitmap o metafile.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


Questo record definisce una stringa di testo basata su un carattere, un rettangolo di layout e un formato.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


Questo record definisce l'origine del rendering alle coordinate orizzontali e verticali specificate. Questo si applica ai pennelli a trama e ai pattern di dithering a 8 e 16 bit per pixel.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


Questo record definisce se abilitare o disabilitare l'anti-aliasing del testo. L'anti-aliasing del testo è un metodo per rendere le linee e i bordi dei glifi dei caratteri più lisci quando vengono disegnati su una superficie di output.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


Questo record definisce il processo utilizzato per il rendering del testo.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


Questo record imposta il contrasto del testo secondo il valore gamma del testo specificato.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


Questo record definisce la modalità di interpolazione di un oggetto in base al tipo specificato di filtraggio dell'immagine. La modalità di interpolazione influenza come viene eseguita la scalatura (allungamento e riduzione).

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


Questo record definisce la modalità di offset dei pixel secondo il valore di centratura dei pixel specificato.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


Questo record definisce la modalità di composizione secondo lo stato del blending alfa, che specifica come i colori di origine vengono combinati con i colori di sfondo.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


Questo record definisce la qualità di composizione, che descrive il livello desiderato di qualità per creare immagini composite da più oggetti.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


Questo record salva lo stato grafico, identificato da un indice specificato, su una pila di stati grafici salvati. Ogni indice della pila è associato a uno stato salvato particolare, e l'indice è utilizzato da un record [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) (sezione 2.3.7.4) per ripristinare lo stato.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


Questo record ripristina lo stato grafico, identificato da un indice specificato, da una pila di stati grafici salvati. Ogni indice della pila è associato a uno stato salvato particolare, e l'indice è definito da un record [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) (sezione 2.3.7.5) per salvare lo stato.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


Questo record apre un nuovo contenitore di stato grafico e specifica una trasformazione per esso. I contenitori grafici sono usati per conservare gli elementi dello stato grafico.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


Questo record apre un nuovo contenitore di stato grafico.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


Questo record chiude un contenitore di stato grafico che era stato precedentemente aperto da un'operazione di avvio del contenitore.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


Questo record definisce la trasformazione dello spazio mondo corrente nel playback device\_context, in base a una matrice di trasformazione specificata.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


Questo record ripristina la trasformazione dello spazio mondo corrente alla matrice identità.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


Questo record moltiplica lo spazio mondo corrente per una matrice di trasformazione specificata.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


Questo record applica una trasformazione di traslazione allo spazio mondo corrente mediante distanze orizzontali e verticali specificate.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


Questo record applica una trasformazione di scala allo spazio mondo corrente mediante fattori di scala orizzontali e verticali specificati.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


Questo record ruota lo spazio mondo corrente di un angolo specificato.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


Questo record specifica fattori di scala aggiuntivi per la trasformazione dello spazio mondo corrente.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


Questo record ripristina la regione di ritaglio corrente per lo spazio mondo all'infinito.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


Questo record combina la regione di ritaglio corrente con un rettangolo.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


Questo record combina la regione di ritaglio corrente con un percorso grafico.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


Questo record combina la regione di ritaglio corrente con un'altra regione grafica.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


Questo record applica una trasformazione di traslazione sulla regione di ritaglio corrente dello spazio mondo.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


Questo record specifica l'output di testo con le posizioni dei caratteri.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


Questo record chiude tutte le figure aperte in un percorso, traccia il contorno del percorso usando la penna corrente e riempie il suo interno usando il pennello corrente.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


Questo record definisce un blocco di parametri di effetti immagine che è stato serializzato in un buffer di dati.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


Questo record specifica lo stato di un contesto dispositivo grafico per un server terminale.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


Questo record specifica le aree di ritaglio nel contesto dispositivo grafico per un server terminale.

