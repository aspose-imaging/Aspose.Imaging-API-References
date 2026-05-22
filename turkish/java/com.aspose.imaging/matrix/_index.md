---
title: "Matrix"
second_title: "Aspose.Imaging for Java API Referansı"
description: "GDI Matrix'i değiştirir."
type: docs
weight: 72
url: /tr/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

GDI+ Matrisini değiştirir.

--------------------

Çoğu algoritma Sun'un AffineTransform.java dosyasından alınmıştır. Matris elemanları için Java'nın dahili kullanılan adları. Java adlarının .net karşılıkları ve açıklamaları haritası: m00 M11 Ölçek X m10 M12 Kayma Y m01 M21 Kayma X m11 M22 Ölçek Y m02 M31 Çevirme X m12 M32 Çevirme Y
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix sınıfının yeni bir örneğini birim matris olarak başlatır. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Yeni bir [Matrix](../../com.aspose.imaging/matrix) sınıfı örneği başlatır. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüm için yeni bir [Matrix](../../com.aspose.imaging/matrix) sınıfı örneği başlatır. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüm için yeni bir [Matrix](../../com.aspose.imaging/matrix) sınıfı örneği başlatır. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | [Matrix](../../com.aspose.imaging/matrix) sınıfının bir kopyasını oluşturur. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Bir birim dönüşüm, çıktı koordinatlarının her zaman giriş koordinatlarıyla aynı olduğu dönüşümdür. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Bir çevirme, vektörlerin uzunluğunu veya açısını değiştirmeden x ve y eksenlerinde koordinatları sabit bir miktar kaydırır. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Bir uniform ölçek, vektörlerin uzunluğunu x ve y yönlerinde aynı miktarda çarpar ve vektörler arasındaki açıyı değiştirmez. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Genel bir ölçek, dik vektörler arasındaki açıyı değiştirmeden, x ve y yönlerinde vektörlerin uzunluğunu farklı miktarlarda çarpar. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Bu sabit, ölçek bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| [TYPE_FLIP](#TYPE-FLIP) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, normalde sağ el koordinat sistemini sol el sistemine değiştiren bir eksen etrafında ayna yansıması yaptığını gösterir. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, 90 derecenin bir katı kadar bir çeyrek dönüş gerçekleştirdiğini gösterir. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, rastgele bir açıyla dönüş yaptığını gösterir. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Bu sabit, dönüşüm bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Bu sabit, bu nesne tarafından tanımlanan dönüşümün giriş koordinatlarının rastgele bir dönüşümünü gerçekleştirdiğini gösterir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | İki matrisin eşit olup olmadığını belirler. |
| [getM11()](#getM11--) | İlk satır ilk sütundaki matris elemanını alır. |
| [getM12()](#getM12--) | İlk satır ikinci sütundaki matris elemanını alır. |
| [getM21()](#getM21--) | İkinci satır ilk sütundaki matris elemanını alır. |
| [getM22()](#getM22--) | İkinci satır ikinci sütundaki matris elemanını alır. |
| [getM31()](#getM31--) | Üçüncü satır ilk sütundaki matris elemanını alır. |
| [getM32()](#getM32--) | Üçüncü satır ilk sütundaki matris elemanını alır. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [getElements()](#getElements--) | Matris elemanlarının bir kopyasını alır. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Bu [Matrix](../../com.aspose.imaging/matrix) tarafından temsil edilen geometrik dönüşümü belirtilen nokta dizisine uygular. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu [Matrix](../../com.aspose.imaging/matrix) üzerine belirtilen sırayla uygular. |
| [scale(float sx, float sy)](#scale-float-float-) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Belirtilen çeviri vektörünü bu Matrix'e belirtilen sırada uygular. |
| [translate(float tx, float ty)](#translate-float-float-) | Belirtilen çeviri vektörünü bu [Matrix](../../com.aspose.imaging/matrix) üzerine (varsayılan) Prepend sırasını kullanarak uygular. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Bu Matrix'i, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırada çarpar. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Bu Matrix'i, matrix parametresinde belirtilen matrisle (varsayılan) Prepend sırasını kullanarak çarpar. |
| [rotate(float angle, int order)](#rotate-float-int-) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşümü, orijinin (sıfır x ve y koordinatları) etrafında belirtilen sırada uygular. |
| [rotate(float angle)](#rotate-float-) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşümü, orijinin (sıfır x ve y koordinatları) etrafında varsayılan (Prepend) sırada uygular. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Belirtilen nokta etrafında saat yönünde bir dönüşümü bu Matrix'e belirtilen sırada uygular. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Belirtilen nokta etrafında saat yönünde bir dönüşümü bu Matrix'e varsayılan (Prepend) sırada uygular. |
| [reset()](#reset--) | Bu Matrisi, birim matrisin elemanlarına sahip olacak şekilde sıfırlar. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `Object`'in bu örnekle eşit olup olmadığını belirler. |
| [isIdentity()](#isIdentity--) | Bu `AffineTransform` bir birim dönüşüm ise `true` döndürür. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix sınıfının yeni bir örneğini birim matris olarak başlatır.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Yeni bir [Matrix](../../com.aspose.imaging/matrix) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m11 | float | m00 M11 Ölçek X |
| m12 | float | m10 M12 Kayma Y |
| m21 | float | m01 M21 Kayma X |
| m22 | float | m11 M22 Ölçek Y |
| m31 | float | m02 M31 Taşıma X |
| m32 | float | m12 M32 Taşıma Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüm için yeni bir [Matrix](../../com.aspose.imaging/matrix) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Dönüştürülecek dikdörtgeni temsil eden bir [RectangleF](../../com.aspose.imaging/rectanglef) yapısı. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | Üst sol, üst sağ ve alt sol köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [PointF](../../com.aspose.imaging/pointf) yapısından oluşan bir dizi. Paralelkenarın alt sağ köşesi, ilk üç köşe tarafından ima edilir. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüm için yeni bir [Matrix](../../com.aspose.imaging/matrix) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Dönüştürülecek dikdörtgeni temsil eden bir [Rectangle](../../com.aspose.imaging/rectangle) yapısı. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | Üst sol, üst sağ ve alt sol köşelerinin dönüştürüleceği paralelkenarın noktalarını temsil eden üç [Point](../../com.aspose.imaging/point) yapısından oluşan bir dizi. Paralelkenarın alt sağ köşesi, ilk üç köşe tarafından ima edilir. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


[Matrix](../../com.aspose.imaging/matrix) sınıfının bir kopyasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | Kopyalama için temel bir matris. |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Bir birim dönüşüm, çıktı koordinatlarının her zaman giriş koordinatlarıyla aynı olduğu bir dönüşümdür. Bu dönüşüm bir birim dönüşümden farklı ise, tür ya sabit GENERAL\_TRANSFORM olacak ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olacaktır.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Bir çevirme, vektörlerin uzunluğunu veya açısını değiştirmeden x ve y eksenlerinde koordinatları sabit bir miktar kaydırır.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Tekdüze bir ölçek, vektörlerin uzunluğunu x ve y yönlerinde aynı miktarda çarpar ve vektörler arasındaki açıyı değiştirmez. Bu bayrak biti, TypeGeneralScale bayrağı ile karşılıklı olarak birbirini dışlar.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Genel bir ölçek, dik vektörler arasındaki açıyı değiştirmeden, vektörlerin uzunluğunu x ve y yönlerinde farklı miktarlarda çarpar. Bu bayrak biti, TypeUniformScale bayrağı ile karşılıklı olarak birbirini dışlar.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Bu sabit, ölçek bayrak bitlerinden herhangi biri için bir bit maskesidir.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, normalde sağ el koordinat sistemini sol el sistemine değiştiren bir eksen etrafında ayna yansıması (flip) yaptığını gösterir. Sağ el koordinat sistemi, pozitif X ekseninin pozitif Y eksenini örtmek üzere saat yönünün tersine döndüğü, başparmağınıza baktığınızda sağ elinizin parmaklarının kıvrıldığı yön gibidir. Sol el koordinat sistemi ise pozitif X ekseninin pozitif Y eksenini örtmek üzere saat yönünde döndüğü, sol elinizin parmaklarının kıvrıldığı yön gibidir. Orijinal çevirme ya da yansıtma dönüşümünün açısını belirlemenin matematiksel bir yolu yoktur, çünkü uygun bir ayarlama dönüşümleriyle tüm çevirme açıları aynı olur. NOT: TypeFlip, GENERAL\_TRANSFORM halka açık hale geldikten sonra eklendi ve bayrak bitleri dış kodda ikili uyumsuzluk yaratmadan yeniden numaralandırılamadı.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, 90 derecenin katları kadar bir çokluğu ile bir çeyrek dönüş (quadrant rotation) yaptığını gösterir. Bir dönüşüm, vektörün açısını, vektörün orijinal yönünden bağımsız olarak aynı miktarda değiştirir ve vektörün uzunluğunu değiştirmez. Bu bayrak biti, TypeGeneralRotation bayrağı ile karşılıklı olarak birbirini dışlar.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak rastgele bir açıyla döndürme yaptığını gösterir. Bir döndürme, vektörün orijinal yönünden bağımsız olarak vektörlerin açılarını aynı miktarda değiştirir ve vektörün uzunluğunu değiştirmez. Bu bayrak biti, ile karşılıklı olarak dışlayıcıdır.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Bu sabit, dönüşüm bayrak bitlerinden herhangi biri için bir bit maskesidir.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Bu sabit, bu nesne tarafından tanımlanan dönüşümün giriş koordinatlarını rastgele bir şekilde dönüştürdüğünü gösterir. Eğer bu dönüşüm yukarıdaki sabitlerden herhangi biriyle sınıflandırılabiliyorsa, tür ya sabit TypeIdentity olur ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olur.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


İki matrisin eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | Karşılaştırılacak ilk matris. |
| b | [Matrix](../../com.aspose.imaging/matrix) | Karşılaştırılacak ikinci matris. |

**Returns:**
boolean - Matrisler eşitse Doğru.
### getM11() {#getM11--}
```
public final float getM11()
```


İlk satır ilk sütundaki matris elemanını alır. X ekseni boyunca ölçeği temsil eder.

**Returns:**
float - İlk satır ilk sütundaki matris elemanı.
### getM12() {#getM12--}
```
public final float getM12()
```


İlk satır ikinci sütundaki matris elemanını alır. Y ekseni boyunca kaymayı temsil eder.

**Returns:**
float - İlk satır ikinci sütundaki matris elemanı.
### getM21() {#getM21--}
```
public final float getM21()
```


İkinci satır ilk sütundaki matris elemanını alır. X ekseni boyunca kaymayı temsil eder.

**Returns:**
float - İkinci satır ilk sütundaki matris elemanı.
### getM22() {#getM22--}
```
public final float getM22()
```


İkinci satır ikinci sütundaki matris elemanını alır. Y ekseni boyunca ölçeği temsil eder.

**Returns:**
float - İkinci satır ikinci sütundaki matris elemanı.
### getM31() {#getM31--}
```
public final float getM31()
```


Üçüncü satır ilk sütundaki matris elemanını alır. X ekseni boyunca çeviriyi temsil eder.

**Returns:**
float - Üçüncü satır ilk sütundaki matris elemanı.
### getM32() {#getM32--}
```
public final float getM32()
```


Üçüncü satır ilk sütundaki matris elemanını alır. Y ekseni boyunca çeviriyi temsil eder.

**Returns:**
float - Üçüncü satır ilk sütundaki matris elemanı.
### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir String.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Matris elemanlarının bir kopyasını alır.

**Returns:**
float[] - Bir matris elemanları kopyası.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Bu [Matrix](../../com.aspose.imaging/matrix) tarafından temsil edilen geometrik dönüşümü belirtilen nokta dizisine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Noktalar. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Belirtilen ölçek vektörünü (scaleX ve scaleY) bu [Matrix](../../com.aspose.imaging/matrix) üzerine belirtilen sırayla uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | float | X ölçeği. |
| scaleY | float | Y ölçeği. |
| sıra | int | Sıra. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Belirtilen ölçek vektörünü (scaleX ve scaleY) bu Matrix'e (varsayılan) Prepend sırasını kullanarak uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Bu sx. Bu sx. Bu sx. |
| sy | float | Bu sy. Bu sy. Bu sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Belirtilen çeviri vektörünü bu Matrix'e belirtilen sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| offsetX | float | Bu offset X. |
| offsetY | float | Bu offset Y. |
| sıra | int | Sıra. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Belirtilen çeviri vektörünü bu [Matrix](../../com.aspose.imaging/matrix) üzerine (varsayılan) Prepend sırasını kullanarak uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tx | float | Bu tx. Bu tx. Bu tx. |
| ty | float | Bu ty. Bu ty. Bu ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Bu Matrix'i, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırada çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Bu tx. Bu tx. Bu tx. |
| sıra | int | Bu sıra. Bu sıra. Bu sıra. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Bu Matrix'i, matrix parametresinde belirtilen matrisle (varsayılan) Prepend sırasını kullanarak çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Bu çarpma yapılacak matris. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşümü, orijinin (sıfır x ve y koordinatları) etrafında belirtilen sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Bu döndürme açısı. |
| sıra | int | Bu matris sırası. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde bir dönüşümü, orijinin (sıfır x ve y koordinatları) etrafında varsayılan (Prepend) sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Bu döndürme açısı. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Belirtilen nokta etrafında saat yönünde bir dönüşümü bu Matrix'e belirtilen sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Bu açı. |
| point | [PointF](../../com.aspose.imaging/pointf) | Bu nokta. |
| sıra | int | Sıra. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Belirtilen nokta etrafında saat yönünde bir dönüşümü bu Matrix'e varsayılan (Prepend) sırada uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Bu açı. |
| point | [PointF](../../com.aspose.imaging/pointf) | Bu nokta. |

### reset() {#reset--}
```
public final void reset()
```


Bu Matrisi, birim matrisin elemanlarına sahip olacak şekilde sıfırlar.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen `Object`'in bu örnekle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu `Object` bu örnek ile karşılaştırmak için. |

**Returns:**
boolean - `true` eğer belirtilen `Object` bu örnek ile eşitse; aksi takdirde `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Bu `AffineTransform` bir birim dönüşüm ise `true` döndürür.

**Returns:**
boolean - `true` eğer bu `AffineTransform` bir birim dönüşümse; aksi takdirde `false`.
