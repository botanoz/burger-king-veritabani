# Burger King Ürün Veritabanı

Bu repo, Burger King ürünlerinin SQL veri dosyasını içerir. Bu veri seti, çeşitli ürünlerin isimlerini, fiyatlarını ve diğer ilgili bilgileri içermektedir.

## İçindekiler

- [Giriş](#giriş)
- [Veri Seti Bilgisi](#veri-seti-bilgisi)
- [Kullanım](#kullanım)
- [Ürünler](#ürünler)
- [Kategoriler](#kategoriler)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## Giriş

Bu repo, Burger King'in ürünlerine ait SQL veri dosyasını barındırır. Bu veri seti, araştırma, analiz veya eğitim amaçlı kullanılabilir.

## Veri Seti Bilgisi

Veri seti, aşağıdaki tabloları içermektedir:

### Categories (Kategoriler)

- `CategoryID`: Kategorinin benzersiz kimliği
- `Name`: Kategorinin adı
- `Description`: Kategorinin açıklaması
- `IsActive`: Kategorinin aktiflik durumu
- `Categoryimg`: Kategoriye ait resim

### Products (Ürünler)

- `ProductID`: Ürünün benzersiz kimliği
- `CategoryID`: Ürünün ait olduğu kategori kimliği
- `Name`: Ürünün adı
- `Description`: Ürünün açıklaması
- `Price`: Ürünün fiyatı
- `StockQuantity`: Ürünün stok miktarı
- `Image`: Ürünün resim bağlantısı
- `IsActive`: Ürünün aktiflik durumu

## Kullanım

Bu veri setini kullanmak için:

1. Repo'yu klonlayın veya zip dosyasını indirin:
    ```bash
    git clone https://github.com/kullaniciadi/burger-king-veritabani.git
    ```

2. SQL dosyasını bir veritabanı yönetim sistemi (örneğin, MySQL veya PostgreSQL) kullanarak içeri aktarın.

3. Veritabanınızı sorgulamaya başlayın ve ihtiyaçlarınıza göre analiz yapın.

## Ürünler

Bu veri setinde yer alan ürünler:

1. Bean Burger Menü
2. Big King Jr Menü
3. Big King Menü
4. Big King XXL Menü
5. BK Steakhouse Burger Menü
6. Cheeseburger Menü
7. Chicken Royale Burger Menü
8. Double Big King Menü
9. Double Cheeseburger Menü
10. Double Kofteburger Menü
11. Double Texas Smokehouse Burger Menü
12. Double Whopper Jr Menü
13. Double Whopper Menü
14. Etli Barbeku Brioche Menü
15. Etli Barbeku Deluxe Burger Menü
16. Fish Royale Menü
17. Hamburger Menü
18. King Beef Burger Menü
19. King Chicken Menü
20. Klasik Gurme Tavuk Menü
21. Kofteburger Menü
22. Mega Double Cheeseburger Menü
23. Rodeo Whopper Menü
24. Spicy Gurme Tavuk Menü
25. Tavukburger Menü
26. Tavuklu Barbeku Brioche Menü
27. Tavuklu Barbeku Deluxe Burger Menü
28. Bean Burger
29. Big King
30. Big King Jr
31. Big King XXL
32. BK Steakhouse Burger
33. Cheeseburger
34. Chicken Royale
35. Double Big King
36. Double Cheeseburger
37. Double King Chicken
38. Double Köfteburger
39. Double Texas Smokehouse Burger
40. Double Whopper Jr
41. Double Whopper
42. Etli Barbeku Brioche
43. Etli Barbeku Deluxe Burger
44. Fish Royale
45. Hamburger
46. King Beef Burger
47. King Chicken
48. Klasik Gurme Tavuk
49. Köfteburger
50. Mega Double Cheeseburger
51. Plant-Based Whopper
52. Rodeo Whopper
53. Spicy Gurme Tavuk
54. Tavuklu Barbeku Brioche
55. Tavuklu Barbeku Deluxe Burger
56. Tavuk Nuggets
57. Tavuk Şeritleri
58. Çıtır Peynir
59. Patates
60. Soğan Halkası
61. Tırtıklı Patates
62. Kids Cheeseburger
63. Kids Hamburger
64. Kids Tavuk Burger
65. Kids Tenders
66. Bkool
67. Çikolatalı Dondurma Kornet
68. Çikolatalı Kurabiye
69. Çikolatalı Parçacıklı Kurabiye
70. Elmalı Tatlı
71. King Sundae
72. Korumalı Koni
73. Koni Dondurma
74. Milkshake Çeşitleri
75. Mini Sundae
76. Sufle
77. Sundae
78. Vişneli Tatlı
79. Ayran 195 ml
80. Ayran 300 ml
81. Cappy Atom 200 ml
82. Cappy Destek 200 ml
83. Çikolatalı Süt
84. Coca Cola
85. Coca Cola Light
86. Coca Cola Zero Sugar
87. Elma Suyu
88. Fanta
89. Fuse Tea
90. Sade Süt
91. Sprite
92. Aci Hardal
93. Mini Aci Sos
94. Mini BBQ
95. Mini Buffalo
96. Mini Ketçap
97. Mini Mayonez
98. Mini Ranch
99. Mini Sarımsaklı Mayonez
100. Truflü Mayonez

## Kategoriler

Bu veri setinde yer alan kategoriler:

1. Menüler
2. Burgerler
3. Çıtır Lezzetler
4. Kids Menüler
5. Tatlılar
6. İçecekler
7. Soslar

## Katkıda Bulunma

Katkılarınızı memnuniyetle karşılıyoruz! Lütfen bir değişiklik yapmadan önce bir issue açın ve ne yapmak istediğinizi açıklayın.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.
