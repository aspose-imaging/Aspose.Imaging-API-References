---
title: "EmfStockObject"
second_title: "Aspose.Imaging for Java API Referansı"
description: "StockObject sayımı, grafik işlemlerinde kullanılabilecek önceden tanımlanmış mantıksal grafik nesnelerinin indekslerini belirtir. Stok nesnelerinin belirli yapıları uygulamaya bağlıdır, ancak stok nesnelerinin özellikleri (SHOULD) aynı türde açıkça oluşturulmuş nesnelerin özelliklerine eşdeğer olmalıdır."
type: docs
weight: 42
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

StockObject sayımı, grafik işlemlerinde kullanılabilecek önceden tanımlanmış mantıksal grafik nesnelerinin indekslerini belirtir. Stok nesnelerinin belirli yapıları uygulamaya bağlıdır; ancak, stok nesnelerinin özellikleri (SHOULD) aynı türde açıkça oluşturulmuş nesnelerin özelliklerine eşdeğer olmalıdır. Bu özellikler, bu sayımda tanımlanan stok nesneleri için mümkün olduğunda belirtilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | Beyaz, katı renkli bir fırça; aşağıdaki özelliklere sahip mantıksal bir fırça (LogBrushEx nesnesi, bölüm 2.2.12) ile eşdeğerdir: BrushStyle: BS\_SOLID (WMF BrushStyle sayımı, [MS-WMF] bölüm 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef nesnesi, [MS-WMF] bölüm 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | Açık gri, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | Gri, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | Koyu gri, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | Siyah, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | Boş bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | Beyaz, katı renkli bir kalem, aşağıdaki özelliklere sahip bir mantıksal kaleme (LogPen nesnesi, bölüm 2.2.19) eşdeğerdir: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle numaralandırması, bölüm 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef nesnesi). |
| [BLACK_PEN](#BLACK-PEN) | Siyah, katı renkli bir kalem, aşağıdaki özelliklere sahip bir mantıksal kaleme eşdeğerdir: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | Boş bir kalem, aşağıdaki özelliklere sahip bir mantıksal kaleme eşdeğerdir: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | Sabit genişlikli, OEM karakter kümesi yazı tipi, aşağıdaki özelliklere sahip bir mantıksal yazı tipine (LogFont nesnesi, bölüm 2.2.13) eşdeğerdir: Charset: OEM\_CHARSET (WMF CharacterSet numaralandırması, [MS-WMF] bölüm 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont numaralandırması, [MS-WMF] bölüm 2.1.1.8) + FIXED\_PITCH (WMF PitchFont numaralandırması, [MS-WMF] bölüm 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | Sabit genişlikli bir yazı tipi, aşağıdaki özelliklere sahip bir mantıksal yazı tipine eşdeğerdir: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | Değişken genişlikli bir yazı tipi, aşağıdaki özelliklere sahip bir mantıksal yazı tipine eşdeğerdir: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | İşletim sisteminde mevcut olması garanti edilen bir yazı tipi. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | Geçerli çıktı cihazı için grafik aygıt sürücüsü tarafından sağlanan varsayılan yazı tipi. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | Geçerli çıktı cihazı için tanımlanan varsayılan palet. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | İşletim sisteminde mevcut olması garanti edilen sabit genişlikli bir yazı tipi. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | İşletim sisteminde mevcut olması garanti edilen sabit genişlikli bir yazı tipi. |
| [DC_BRUSH](#DC-BRUSH) | Oynatma aygıt bağlamında şu anda seçili olan katı renkli fırça |
| [DC_PEN](#DC-PEN) | Oynatma aygıt bağlamında şu anda seçili olan katı renkli kalem |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


Beyaz, katı renkli bir fırça; aşağıdaki özelliklere sahip mantıksal bir fırça (LogBrushEx nesnesi, bölüm 2.2.12) ile eşdeğerdir: BrushStyle: BS\_SOLID (WMF BrushStyle sayımı, [MS-WMF] bölüm 2.1.1.4) Color: 0x00FFFFFF (WMF ColorRef nesnesi, [MS-WMF] bölüm 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


Açık gri, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


Gri, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


Koyu gri, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


Siyah, katı renkli bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


Boş bir fırça, aşağıdaki özelliklere sahip bir mantıksal fırçaya eşdeğerdir: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


Beyaz, katı renkli bir kalem, aşağıdaki özelliklere sahip bir mantıksal kaleme (LogPen nesnesi, bölüm 2.2.19) eşdeğerdir: PenStyle: PS\_COSMETIC + PS\_SOLID (PenStyle numaralandırması, bölüm 2.1.25) ColorRef: 0x00FFFFFF (WMF ColorRef nesnesi).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


Siyah, katı renkli bir kalem, aşağıdaki özelliklere sahip bir mantıksal kaleme eşdeğerdir: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


Boş bir kalem, aşağıdaki özelliklere sahip bir mantıksal kaleme eşdeğerdir: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


Sabit genişlikli, OEM karakter kümesi yazı tipi, aşağıdaki özelliklere sahip bir mantıksal yazı tipine (LogFont nesnesi, bölüm 2.2.13) eşdeğerdir: Charset: OEM\_CHARSET (WMF CharacterSet numaralandırması, [MS-WMF] bölüm 2.1.1.5) PitchAndFamily: FF\_DONTCARE (WMF FamilyFont numaralandırması, [MS-WMF] bölüm 2.1.1.8) + FIXED\_PITCH (WMF PitchFont numaralandırması, [MS-WMF] bölüm 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


Sabit genişlikli bir yazı tipi, aşağıdaki özelliklere sahip bir mantıksal yazı tipine eşdeğerdir: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


Değişken genişlikli bir yazı tipi, aşağıdaki özelliklere sahip bir mantıksal yazı tipine eşdeğerdir: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


İşletim sisteminde mevcut olması garanti edilen bir yazı tipi. Bu değer tarafından belirtilen gerçek yazı tipi uygulamaya bağlıdır

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


Geçerli çıktı cihazı için grafik aygıt sürücüsü tarafından sağlanan varsayılan yazı tipi. Bu değer tarafından belirtilen gerçek yazı tipi uygulamaya bağlıdır

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


Geçerli çıktı cihazı için tanımlanan varsayılan palet. Bu değer tarafından belirtilen gerçek palet uygulamaya bağlıdır

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


İşletim sisteminde mevcut olması garanti edilen sabit genişlikli bir yazı tipi. Bu değer tarafından belirtilen gerçek yazı tipi uygulamaya bağlıdır

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


İşletim sisteminde mevcut olması garanti edilen sabit genişlikli bir yazı tipi. Bu değer tarafından belirtilen gerçek yazı tipi uygulamaya bağlıdır

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


Oynatma aygıt bağlamında şu anda seçili olan katı renkli fırça

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


Oynatma aygıt bağlamında şu anda seçili olan katı renkli kalem

