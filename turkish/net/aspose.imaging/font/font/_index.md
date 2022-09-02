---
title: Font
second_title: Aspose.Imaging for .NET API Referansı
description: Yeni bir başlangıç başlatırFontaspose.imaging/font belirtilen mevcutFontaspose.imaging/font veFontStyleaspose.imaging/fontstyle numaralandırma.
type: docs
weight: 10
url: /tr/net/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

Yeni bir başlangıç başlatır[`Font`](../../font) belirtilen mevcut[`Font`](../../font) ve[`FontStyle`](../../fontstyle) numaralandırma.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| prototype | Font | Var olan[`Font`](../../font) hangi yeni oluşturmak için[`Font`](../../font). |
| newStyle | FontStyle | bu[`FontStyle`](../../fontstyle)yenisine başvurmak[`Font`](../../font) . Birden çok değer[`FontStyle`](../../fontstyle) numaralandırma VEYA operatörü ile birleştirilebilir. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *prototype* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* ad alanı [Aspose.Imaging](../../font)
* toplantı [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

Yeni bir başlangıç başlatır[`Font`](../../font) belirli bir boyutu kullanarak. Karakter seti şu şekilde ayarlandı:Default , grafik birimiPoint , yazı tipi stiliRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | bir dize temsili[`Font`](../../font) isim. |
| emSize | Single | Yeni yazı tipinin punto cinsinden em boyutu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya 0'a eşit, sonsuz olarak değerlendiriliyor veya geçerli bir sayı değil. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* class [Font](../../font)
* ad alanı [Aspose.Imaging](../../font)
* toplantı [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Yeni bir başlangıç başlatır[`Font`](../../font) belirli bir boyut ve stil kullanarak. Karakter seti şu şekilde ayarlandı:Default , grafik birimiPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | bir dize temsili[`Font`](../../font) isim. |
| emSize | Single | Yeni yazı tipinin punto cinsinden em boyutu. |
| style | FontStyle | bu[`FontStyle`](../../fontstyle) yeni yazı tipi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya 0'a eşit, sonsuz olarak değerlendiriliyor veya geçerli bir sayı değil. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* ad alanı [Aspose.Imaging](../../font)
* toplantı [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Yeni bir başlangıç başlatır[`Font`](../../font) belirli bir boyut ve birim kullanarak. Karakter seti şu şekilde ayarlandı:Default , stil ayarlanırRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | bir dize temsili[`Font`](../../font) isim. |
| emSize | Single | tarafından belirtilen birimlerde yeni yazı tipinin em-boyutu*unit* parametre. |
| unit | GraphicsUnit | bu[`GraphicsUnit`](../../graphicsunit) yeni yazı tipi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya 0'a eşit, sonsuz olarak değerlendiriliyor veya geçerli bir sayı değil. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* ad alanı [Aspose.Imaging](../../font)
* toplantı [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Yeni bir başlangıç başlatır[`Font`](../../font) belirtilen bir boyut, stil, birim ve karakter seti kullanarak.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | bir dize temsili[`Font`](../../font) isim. |
| emSize | Single | tarafından belirtilen birimlerde yeni yazı tipinin em-boyutu*unit* parametre. |
| style | FontStyle | bu[`FontStyle`](../../fontstyle) yeni yazı tipi. |
| unit | GraphicsUnit | bu[`GraphicsUnit`](../../graphicsunit) yeni yazı tipi. |
| characterSet | CharacterSet | Bu yazı tipi için kullanılacak bir karakter kümesi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya 0'a eşit, sonsuz olarak değerlendiriliyor veya geçerli bir sayı değil. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* ad alanı [Aspose.Imaging](../../font)
* toplantı [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Yeni bir başlangıç başlatır[`Font`](../../font) belirtilen bir boyut, stil ve birim kullanarak.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | bir dize temsili[`Font`](../../font) isim. |
| emSize | Single | tarafından belirtilen birimlerde yeni yazı tipinin em-boyutu*unit* parametre. |
| style | FontStyle | bu[`FontStyle`](../../fontstyle) yeni yazı tipi. |
| unit | GraphicsUnit | bu[`GraphicsUnit`](../../graphicsunit) yeni yazı tipi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya 0'a eşit, sonsuz olarak değerlendiriliyor veya geçerli bir sayı değil. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* ad alanı [Aspose.Imaging](../../font)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
