---
title: "EmfMapMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione MapMode è usata per definire l'unità di misura per trasformare le unità di spazio pagina in unità di spazio dispositivo e per definire l'orientamento degli assi di disegno."
type: docs
weight: 30
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

L'enumerazione MapMode è usata per definire l'unità di misura per trasformare le unità di spazio pagina in unità di spazio dispositivo e per definire l'orientamento degli assi di disegno.
## Campi

| Campo | Descrizione |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | Ogni unità logica è mappata a un pixel del dispositivo. |
| [MM_LOMETRIC](#MM-LOMETRIC) | Ogni unità logica è mappata a 0,1 millimetro. |
| [MM_HIMETRIC](#MM-HIMETRIC) | Ogni unità logica è mappata a 0,01 millimetro. |
| [MM_LOENGLISH](#MM-LOENGLISH) | Ogni unità logica è mappata a 0,01 pollice. |
| [MM_HIENGLISH](#MM-HIENGLISH) | Ogni unità logica è mappata a 0,001 pollice. |
| [MM_TWIPS](#MM-TWIPS) | Ogni unità logica è mappata a un ventesimo di un punto di stampa (1/1440 di pollice, anche chiamato "twip"). |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | Le unità logiche sono mappate a unità arbitrarie con assi scalati in modo uguale; cioè, un'unità lungo l'asse x è uguale a un'unità lungo l'asse y. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | Le unità logiche sono mappate a unità arbitrarie con assi scalati arbitrariamente. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


Ogni unità logica è mappata a un pixel del dispositivo. L'asse x positivo è verso destra; l'asse y positivo è verso il basso.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


Ogni unità logica è mappata a 0,1 millimetro. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


Ogni unità logica è mappata a 0,01 millimetro. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


Ogni unità logica è mappata a 0,01 pollice. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


Ogni unità logica è mappata a 0,001 pollice. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


Ogni unità logica è mappata a un ventesimo di un punto di stampa (1/1440 di pollice, anche chiamato "twip"). L'asse x positivo è verso destra; l'asse y positivo è verso l'alto.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


Le unità logiche sono mappate a unità arbitrarie con assi scalati in modo uguale; cioè, un'unità lungo l'asse x è uguale a un'unità lungo l'asse y. I record EMR\_SETWINDOWEXTEX e EMR\_SETVIEWPORTEXTEX DEVE essere usati per specificare le unità e l'orientamento degli assi. Gli aggiustamenti DEVE essere effettuati, se necessario, per garantire che le unità x e y rimangano della stessa dimensione. Per esempio, quando l'estensione della finestra è impostata, la viewport DEVE essere regolata per mantenere le unità isotrope.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


Le unità logiche sono mappate a unità arbitrarie con assi scalati arbitrariamente. I record EMR\_SETWINDOWEXTEX e EMR\_SETVIEWPORTEXTEX DEVONO essere usati per specificare le unità, l'orientamento e la scala.

