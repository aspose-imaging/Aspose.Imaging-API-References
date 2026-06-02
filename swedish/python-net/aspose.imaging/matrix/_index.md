---
title: "Matrix‑klass"
type: docs
weight: 6070
url: /sv/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Matrix()](#Matrix__1) | Initierar en ny instans av Matrix‑klassen som identitetsmatris. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Skapar en kopia av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| TYPE_FLIP [statisk] | int | r | Denna flaggbit indikerar att den transform som definieras av detta objekt<br/>            utför en spegelvändning kring någon axel som förändrar det<br/>            normalt högrehandskoordinatsystemet till ett vänsterhands<br/>            system utöver de konverteringar som anges av andra flaggbitar.<br/>            Ett högrehandskoordinatsystem är ett där den positiva X-axeln roterar moturs för att överlappa den positiva Y-axeln<br/>            liknande den riktning som fingrarna på din högra hand<br/>            kröker när du tittar rakt på tummen.<br/>            Ett vänsterhandskoordinatsystem är ett där den positiva X-axeln roterar medurs för att överlappa den positiva Y-axeln liknande<br/>            den riktning som fingrarna på din vänstra hand kröker.<br/>            Det finns inget matematiskt sätt att bestämma vinkeln för den<br/>            ursprungliga flip- eller spegeltransformen eftersom alla vinklar<br/>            av flip är identiska givet en lämplig justerande rotation.<br/>            OBS: TypeFlip lades till efter att GENERAL_TRANSFORM var i offentlig<br/>            cirkulation och flaggbitarna kunde inte längre omnumreras på ett praktiskt sätt<br/>            utan att introducera binär inkompatibilitet i extern<br/>            kod. |
| TYPE_GENERAL_ROTATION [static] | int | r | Denna flaggbit indikerar att den transform som definieras av detta objekt<br/>            utför en rotation med en godtycklig vinkel utöver de<br/>            konverteringar som anges av andra flaggbitar.<br/>            En rotation förändrar vektorns vinklar med samma mängd<br/>            oavsett vektorns ursprungliga riktning och utan att<br/>            ändra vektorns längd.<br/>            Denna flaggbit är ömsesidigt uteslutande med den |
| TYPE_GENERAL_SCALE [static] | int | r | En allmän skalning multiplicerar längden på vektorer med olika<br/>            mängder i x- och y-riktningarna utan att förändra vinkeln<br/>            mellan vinkelräta vektorer.<br/>            Denna flaggbit är ömsesidigt uteslutande med flaggan TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Denna konstant indikerar att den transform som definieras av detta objekt<br/>            utför en godtycklig konvertering av inmatningskoordinaterna.<br/>            Om denna transform kan klassificeras av någon av ovanstående konstanter,<br/>            kommer typen antingen att vara konstanten TypeIdentity eller en<br/>            kombination av de lämpliga flaggbitarna för de olika koordinat<br/>            konverteringarna som denna transform utför. |
| TYPE_IDENTITY [static] | int | r | En identitetstransform är en där utdata-koordinaterna alltid är<br/>            desamma som indata-koordinaterna.<br/>            Om denna transform är något annat än identitetstransformen,<br/>            kommer typen antingen att vara konstanten GENERAL_TRANSFORM eller en<br/>            kombination av de lämpliga flaggbitarna för de olika koordinat<br/>            konverteringarna som denna transform utför. |
| TYPE_MASK_ROTATION [static] | int | r | Denna konstant är en bitmask för någon av rotationsflaggbitarna. |
| TYPE_MASK_SCALE [static] | int | r | Denna konstant är en bitmask för någon av skalningsflaggbitarna. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Denna flaggbit indikerar att den transform som definieras av detta objekt<br/>            utför en kvadrantrotation med någon multipel av 90 grader i<br/>            tillägg till de konverteringar som anges av andra flaggbitar.<br/>            En rotation förändrar vektorns vinklar med samma mängd<br/>            oavsett vektorns ursprungliga riktning och utan att<br/>            ändra vektorns längd.<br/>            Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | En translation förflyttar koordinaterna med ett konstant värde i x<br/>            och y utan att ändra vektorns längd eller vinkel. |
| TYPE_UNIFORM_SCALE [static] | int | r | En enhetlig skalning multiplicerar längden på vektorer med samma mängd<br/>            i både x- och y-riktningarna utan att förändra vinkeln mellan<br/> vektorer. |
| elements | float[] | r | Hämtar en array av flyttal som representerar elementen i denna [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| m11 | float | r | Hämtar matriselementet i första raden första kolumnen. Representerar skalning längs X-axeln. |
| m12 | float | r | Hämtar matriselementet i första raden andra kolumnen. Representerar skevning längs Y-axeln. |
| m21 | float | r | Hämtar matriselementet i andra raden första kolumnen. Representerar skevning längs X-axeln. |
| m22 | float | r | Hämtar matriselementet i andra raden andra kolumnen. Representerar skalning längs Y-axeln. |
| m31 | float | r | Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs X-axeln. |
| m32 | float | r | Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs Y-axeln. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
| [get_elements()](#get_elements__3) | Hämtar en kopia av matrisens element. |
| [multiply(t_tx)](#multiply_t_tx_4) | Multiplicerar denna Matrix med matrisen som anges i matrisparametern med (standard) Prepend order. |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | Multiplicerar denna Matrix med matrisen som anges i matrisparametern, och i den ordning som anges i order-parametern. |
| reset() | Återställer denna Matrix så att den har element från identitetsmatrisen. |
| [rotate(angle)](#rotate_angle_6) | Tillämpar en medurs rotation i den mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i standard (Prepend) ordning. |
| [rotate(angle, order)](#rotate_angle_order_7) | Tillämpar en medurs rotation i den mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i den angivna ordningen. |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | Tillämpar en medurs rotation kring den angivna punkten på denna Matrix i standard (Prepend) ordning. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | Tillämpar en medurs rotation kring den angivna punkten på denna Matrix i den angivna ordningen. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | Tillämpar den angivna skalningsvektorn (scaleX och scaleY) på denna [Matrix](/imaging/python-net/aspose.imaging/matrix/) med den angivna ordningen. |
| [scale(sx, sy)](#scale_sx_sy_11) | Tillämpar den angivna skalningsvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend order. |
| [transform_points(points)](#transform_points_points_12) | Tillämpar den geometriska transformen som representeras av denna [Matrix](/imaging/python-net/aspose.imaging/matrix/) på en angiven punktarray. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | Tillämpar den angivna transvektorn på denna Matrix i den angivna ordningen. |
| [translate(tx, ty)](#translate_tx_ty_14) | Tillämpar den angivna transvektorn på denna [Matrix](/imaging/python-net/aspose.imaging/matrix/) med (standard) Prepend order. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Initierar en ny instans av Matrix‑klassen som identitetsmatris.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| m11 | float | m00     M11     Scale X |
| m12 | float | m10     M12     Shear Y |
| m21 | float | m01     M21     Shear X |
| m22 | float | m11     M22     Scale Y |
| m31 | float | m02     M31     Translate X |
| m32 | float | m12     M32     Översätt Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Skapar en kopia av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | En basmatris för coping |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av tre [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar punkterna i ett parallellogram till vilket de övre vänstra, övre högra och nedre vänstra hörnen av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | En array av tre [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar punkterna i ett parallellogram till vilket de övre vänstra, övre högra och nedre vänstra hörnen av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | En array av tre [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar punkterna i ett parallellogram till vilket de övre vänstra, övre högra och nedre vänstra hörnen av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

Initierar en ny instans av klassen [Matrix](/imaging/python-net/aspose.imaging/matrix/) till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | En [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | En array av tre [PointF](/imaging/python-net/aspose.imaging/pointf/) strukturer som representerar punkterna i ett parallellogram till vilket de övre vänstra, övre högra och nedre vänstra hörnen av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

Hämtar en kopia av matrisens element.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float[] | En kopia av matrisens element. |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

Multiplicerar denna Matrix med matrisen som anges i matrisparametern med (standard) Prepend order.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att multiplicera med. |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

Multiplicerar denna Matrix med matrisen som anges i matrisparametern, och i den ordning som anges i order-parametern.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Tx‑värdet. Tx‑värdet. Tx‑värdet. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen. Ordningen. Ordningen. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

Tillämpar en medurs rotation i den mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i standard (Prepend) ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

Tillämpar en medurs rotation i den mängd som anges i vinkel‑parametern, kring origo (noll x‑ och y‑koordinater) för denna Matrix i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Matrisordningen. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

Tillämpar en medurs rotation kring den angivna punkten på denna Matrix i standard (Prepend) ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Punkten. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

Tillämpar en medurs rotation kring den angivna punkten på denna Matrix i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Punkten. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

Tillämpar den angivna skalningsvektorn (scaleX och scaleY) på denna [Matrix](/imaging/python-net/aspose.imaging/matrix/) med den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_x | float | Skala X. |
| scale_y | float | Skala Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen. |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

Tillämpar den angivna skalningsvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend order.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Sx‑värdet. Sx‑värdet. Sx‑värdet. |
| sy | float | Sy‑värdet. Sy‑värdet. Sy‑värdet. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

Tillämpar den geometriska transformen som representeras av denna [Matrix](/imaging/python-net/aspose.imaging/matrix/) på en angiven punktarray.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punkterna. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

Tillämpar den angivna transvektorn på denna Matrix i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| offset_x | float | Offset X‑värdet. |
| offset_y | float | Offset Y‑värdet. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ordningen. |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

Tillämpar den angivna transvektorn på denna [Matrix](/imaging/python-net/aspose.imaging/matrix/) med (standard) Prepend order.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tx | float | Tx‑värdet. Tx‑värdet. Tx‑värdet. |
| ty | float | Ty‑värdet. Ty‑värdet. Ty‑värdet. |

