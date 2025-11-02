# 1. Ad ve Soyadı Alıp Tam Adı Yazdıran Program
ad = input("Adınızı girin: ")
soyad = input("Soyadınızı girin: ")
print("Tam adınız:", ad, soyad)

# 2. İki Sayının Toplamı, Farkı ve Çarpımı
sayi1 = int(input("Birinci sayıyı girin: "))
sayi2 = int(input("İkinci sayıyı girin: "))
print("Toplam:", sayi1 + sayi2)
print("Fark:", sayi1 - sayi2)
print("Çarpım:", sayi1 * sayi2)

# 3. Yaş 18’den Büyük mü?
yas = int(input("Yaşınızı girin: "))
print("18 yaşından büyük mü?", yas > 18)

# 4. Dikdörtgen Alanı ve Çevresi
kisa = int(input("Kısa kenarı girin: "))
uzun = int(input("Uzun kenarı girin: "))
alan = kisa * uzun
cevre = 2 * (kisa + uzun)
print("Alan:", alan)
print("Çevre:", cevre)

# 5. Sayı Pozitif mi?
sayi = int(input("Bir sayı girin: "))
print("Sayı pozitif mi?", sayi > 0)

# 6. Kelimenin İlk 3 ve Son 2 Harfi
kelime = input("Bir kelime girin: ")
print("İlk 3 harf:", kelime[0:3])
print("Son 2 harf:", kelime[-2:])

# 7. İki Sayının Ortalaması
sayi1 = int(input("Birinci sayıyı girin: "))
sayi2 = int(input("İkinci sayıyı girin: "))
ortalama = (sayi1 + sayi2) / 2
print("Ortalama:", float(ortalama))

# 8. Her İki Sayı da Çift mi?
sayi1 = int(input("Birinci sayıyı girin: "))
sayi2 = int(input("İkinci sayıyı girin: "))
print("İkisi de çift mi?", sayi1 % 2 == 0 and sayi2 % 2 == 0)

# 9. Metin Uzunluğu ve Büyük Harf Hali
metin = input("Bir metin girin: ")
print("Metnin uzunluğu:", len(metin))
print("Büyük harf hali:", metin.upper())

# 10. Dairenin Alanı (π = 3.14)
pi = 3.14
r = float(input("Dairenin yarıçapını girin: "))
alan = pi * (r ** 2)
print("Dairenin alanı:", alan)

# 11. İki Sayı Eşit mi? Büyüklük Karşılaştırması
sayi1 = int(input("Birinci sayıyı girin: "))
sayi2 = int(input("İkinci sayıyı girin: "))
print("Eşit mi?", sayi1 == sayi2)
print("Birinci sayı ikinciden büyük mü?", sayi1 > sayi2)

# 12. Sayı Hem 3’e Hem 5’e Bölünüyor mu?
sayi = int(input("Bir sayı girin: "))
print("Hem 3'e hem 5'e tam bölünüyor mu?", sayi % 3 == 0 and sayi % 5 == 0)




