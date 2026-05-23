---
title: "Matrix Sınıfı"
type: docs
weight: 6070
url: /tr/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Matrix()](#Matrix__1) | Matrix sınıfının yeni bir örneğini birim matris olarak başlatır. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır. |
| [Matrix(origin)](#Matrix_origin_3) | [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfının bir kopyasını oluşturur. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün<br/>            bir eksen etrafında ayna görüntüsü çevirmesi yaptığını ve<br/>            normalde sağ el koordinat sistemini sol el sistemine<br/>            dönüştürdüğünü, ayrıca diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak<br/>            gösterir.<br/>            Sağ el koordinat sistemi, pozitif X ekseninin saat yönünün tersine dönerek pozitif Y eksenini<br/>            örtmesi durumudur; bu, başparmağınıza baktığınızda sağ elinizin parmaklarının kıvrıldığı yönle benzerdir.<br/>            Sol el koordinat sistemi, pozitif X ekseninin saat yönünde dönerek pozitif Y eksenini<br/>            örtmesi durumudur; bu, sol elinizin parmaklarının kıvrıldığı yönle benzerdir.<br/>            Orijinal çevirme veya ayna dönüşümünün açısını belirlemenin matematiksel bir yolu yoktur, çünkü uygun bir ayar dönüşü ile tüm çevirme açıları aynı olur.<br/>            NOT: TypeFlip, GENERAL_TRANSFORM genel olarak yayımlandıktan sonra eklendi ve bayrak bitleri dış kodda ikili uyumsuzluk yaratmadan rahatça yeniden numaralandırılamadı. |
| TYPE_GENERAL_ROTATION [static] | int | r | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün<br/>            rastgele bir açıyla döndürme yaptığı ve diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak<br/>            gerçekleştiğini gösterir.<br/>            Bir döndürme, vektörlerin açılarını aynı miktarda değiştirir<br/>            vektörün orijinal yönünden bağımsız olarak ve vektörün uzunluğunu değiştirmeden.<br/>            Bu bayrak biti, şununla karşılıklı olarak dışlayıcıdır: |
| TYPE_GENERAL_SCALE [static] | int | r | Genel bir ölçek, vektörlerin uzunluğunu x ve y yönlerinde farklı<br/>            miktarlarda çarpar ve dik vektörler arasındaki açıyı değiştirmez.<br/>            Bu bayrak biti, TypeUniformScale bayrağıyla karşılıklı olarak dışlayıcıdır. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Bu sabit, bu nesne tarafından tanımlanan dönüşümün<br/>            giriş koordinatlarının rastgele bir dönüşümünü gerçekleştirir.<br/>            Bu dönüşüm yukarıdaki sabitlerden herhangi biriyle sınıflandırılabiliyorsa,<br/>            tür ya TypeIdentity sabiti ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat<br/>            dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olacaktır. |
| TYPE_IDENTITY [static] | int | r | Bir kimlik dönüşümü, çıktı koordinatlarının<br/>            her zaman giriş koordinatlarıyla aynı olduğu bir dönüşümdür.<br/>            Bu dönüşüm kimlik dönüşümü dışında bir şey ise,<br/>            tür ya GENERAL_TRANSFORM sabiti ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat<br/>            dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olacaktır. |
| TYPE_MASK_ROTATION [static] | int | r | Bu sabit, döndürme bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| TYPE_MASK_SCALE [static] | int | r | Bu sabit, ölçek bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün<br/>            diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak 90 derecelik katlarıyla bir çeyrek döndürme yaptığı anlamına gelir.<br/>            Bir döndürme, vektörlerin açılarını aynı miktarda değiştirir<br/>            vektörün orijinal yönünden bağımsız olarak ve vektörün uzunluğunu değiştirmeden.<br/>            Bu bayrak biti, TypeGeneralRotation bayrağıyla karşılıklı olarak dışlayıcıdır. |
| TYPE_TRANSLATION [static] | int | r | Bir çeviri, koordinatları x ve y yönlerinde sabit bir miktar hareket ettirir<br/>            ve vektörlerin uzunluğunu veya açısını değiştirmez. |
| TYPE_UNIFORM_SCALE [static] | int | r | Tekdüzen bir ölçek, vektörlerin uzunluğunu x ve y yönlerinde aynı miktarda çarpar<br/>            ve vektörler arasındaki açıyı değiştirmez.<br/>            Bu bayrak biti, TypeGeneralScale bayrağıyla karşılıklı olarak dışlayıcıdır. |
| elements | float[] | r | Bu [Matrix](/imaging/python-net/aspose.imaging/matrix/) öğesinin elemanlarını temsil eden kayan nokta değerlerinden oluşan bir dizi alır. |
| m11 | float | r | İlk satır ilk sütundaki matris elemanını alır. X ekseni boyunca ölçeği temsil eder. |
| m12 | float | r | İlk satır ikinci sütundaki matris elemanını alır. Y ekseni boyunca kaymayı temsil eder. |
| m21 | float | r | İkinci satır birinci sütundaki matrix öğesini alır. X ekseni boyunca kayma temsil eder. |
| m22 | float | r | İkinci satır ikinci sütundaki matrix öğesini alır. Y ekseni boyunca ölçekleme temsil eder. |
| m31 | float | r | Üçüncü satır birinci sütundaki matrix öğesini alır. X ekseni boyunca çevirme temsil eder. |
| m32 | float | r | Üçüncü satır birinci sütundaki matrix öğesini alır. Y ekseni boyunca çevirme temsil eder. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır. |
| [get_elements()](#get_elements__3) | Matrix öğelerinin bir kopyasını alır. |
| [multiply(t_tx)](#multiply_t_tx_4) | Bu Matrix'i, matrix parametresinde belirtilen matrix ile (varsayılan) Prepend sırasını kullanarak çarpar. |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | Bu Matrix'i, matrix parametresinde belirtilen matrix ile ve order parametresinde belirtilen sırada çarpar. |
| reset() | Bu Matrix'i, birim matrix öğelerine sahip olacak şekilde sıfırlar. |
| [rotate(angle)](#rotate_angle_6) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde döndürmeyi, orijinin (sıfır x ve y koordinatları) etrafında, varsayılan (Prepend) sırada uygular. |
| [rotate(angle, order)](#rotate_angle_order_7) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde döndürmeyi, orijinin (sıfır x ve y koordinatları) etrafında, belirtilen sırada uygular. |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | Belirtilen nokta etrafında saat yönünde döndürmeyi, bu Matrix'e varsayılan (Prepend) sırada uygular. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | Belirtilen nokta etrafında saat yönünde döndürmeyi, bu Matrix'e belirtilen sırada uygular. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen sırada uygular. |
| [scale(sx, sy)](#scale_sx_sy_11) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular. |
| [transform_points(points)](#transform_points_points_12) | Bu [Matrix](/imaging/python-net/aspose.imaging/matrix/) tarafından temsil edilen geometrik dönüşümü, belirtilen bir nokta dizisine uygular. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | Belirtilen çevirme vektörünü bu Matrix'e belirtilen sırada uygular. |
| [translate(tx, ty)](#translate_tx_ty_14) | Belirtilen çevirme vektörünü bu [Matrix](/imaging/python-net/aspose.imaging/matrix/) (varsayılan) Prepend sırasını kullanarak uygular. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Matrix sınıfının yeni bir örneğini birim matris olarak başlatır.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| m11 | float | m00     M11     Ölçek X |
| m12 | float | m10     M12     Kayma Y |
| m21 | float | m01     M21     Kayma X |
| m22 | float | m11     M22     Ölçek Y |
| m31 | float | m02     M31     Çevirme X |
| m32 | float | m12     M32     Translate Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

[Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfının bir kopyasını oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Kopyalama için temel bir matris |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dönüştürülecek dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısından oluşan bir dizi. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dönüştürülecek dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısından oluşan bir dizi. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dönüştürülecek dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısından oluşan bir dizi. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre yeni bir [Matrix](/imaging/python-net/aspose.imaging/matrix/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dönüştürülecek dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısından oluşan bir dizi. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

Matrix öğelerinin bir kopyasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float[] | Bir matris öğeleri kopyası. |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

Bu Matrix'i, matrix parametresinde belirtilen matrix ile (varsayılan) Prepend sırasını kullanarak çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Çarpma işlemi yapılacak matris. |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

Bu Matrix'i, matrix parametresinde belirtilen matrix ile ve order parametresinde belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | tx. tx. tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | sıra. sıra. sıra. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde döndürmeyi, orijinin (sıfır x ve y koordinatları) etrafında, varsayılan (Prepend) sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönme açısı. |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde döndürmeyi, orijinin (sıfır x ve y koordinatları) etrafında, belirtilen sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönme açısı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Matris sırası. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

Belirtilen nokta etrafında saat yönünde döndürmeyi, bu Matrix'e varsayılan (Prepend) sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Açı. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Nokta. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

Belirtilen nokta etrafında saat yönünde döndürmeyi, bu Matrix'e belirtilen sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Açı. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Nokta. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Sıra. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

Belirtilen ölçek vektörünü (scaleX ve scaleY) bu [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| scale_x | float | X ölçeği. |
| scale_y | float | Y ölçeği. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Sıra. |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

Bu [Matrix](/imaging/python-net/aspose.imaging/matrix/) tarafından temsil edilen geometrik dönüşümü, belirtilen bir nokta dizisine uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Noktalar. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

Belirtilen çevirme vektörünü bu Matrix'e belirtilen sırada uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| offset_x | float | X ofseti. |
| offset_y | float | Y ofseti. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Sıra. |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

Belirtilen çevirme vektörünü bu [Matrix](/imaging/python-net/aspose.imaging/matrix/) (varsayılan) Prepend sırasını kullanarak uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tx | float | tx. tx. tx. |
| ty | float | ty. ty. ty. |

