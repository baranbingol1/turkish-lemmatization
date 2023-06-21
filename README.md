# turkish-lemmatization

Bu python scripti zeyrek kütüphanesini kullanarak verilen türkçe metni lemmatize edilmiş halde çıkarır.

# Scriptin Çalışma Mantığı

Gördüğü kelimeleri tekrar işlememek için bir hash table oluşturur.

Zeyrek kütüphanesi verilen kelimeyi köklerine ayırır ve birden fazla seçenek geri döndürür örneğin "adam" kelimesi için "ada" ve "adam" köklerini döndürür.

Her bir input için program şöyle çalışır:
Eğer döndürdüğü kelime kökleri arasında verilen input ile aynı kök varsa o kökü hash table'a sok.
Eğer yoksa döndürdüğü ilk kökü hash table'a sok.
