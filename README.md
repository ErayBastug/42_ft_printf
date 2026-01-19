# 42_ft_printf

Bu proje, C dilindeki standart `printf` fonksiyonunun temel işlevlerini sıfırdan yeniden yazarak oluşturulmuş bir kütüphanedir.

## Projenin Özeti
Projenin temel amacı, **Variadic Functions** (değişken sayıda argüman alan fonksiyonlar) mantığını kullanarak, farklı veri tiplerini (`int`, `char`, `hex`, `pointer` vb.) formatlayıp ekrana yazdırmaktır.

## Teknik Özellikler
* **Variadic Arguments:** `stdarg.h` kütüphanesi kullanılarak belirsiz sayıda parametre yönetimi sağlandı.
* **Veri Dönüşümü:** Sayısal verilerin (decimal, hexadecimal) ve bellek adreslerinin (pointers) metne dönüştürülüp yazdırılması için algoritmalar geliştirildi.
* **Format Desteği:** `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, `%X` ve `%%` belirleyicileri desteklenmektedir.
