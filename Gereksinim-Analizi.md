1. Araç Fotoğraf İşlemleri

API Metodu:

1.1 POST /vehicles/{vehicleId}/images

1.2 PUT /vehicles/{vehicleId}/images/{imageId}

1.3 DELETE /vehicles/{vehicleId}/images/{imageId}

Açıklama: Araçlara fotoğraf ekleme, mevcut fotoğrafı güncelleme ve silme işlemlerini sağlar.

2. Araç Bilgileri İşlemleri

2.1 API Metodu:

2.2 POST /vehicles

2.3 PUT /vehicles/{vehicleId}

2.4 DELETE /vehicles/{vehicleId}

Açıklama: Araç bilgilerini (marka, model, yıl, fiyat, kilometre vb.) ekleme, güncelleme ve silme işlemlerini sağlar.

4. Mesaj Kutusu İşlemleri

4.1 API Metodu:

4.2 POST /messages

4.3 PUT /messages/{messageId}

4.4 DELETE /messages/{messageId}

Açıklama: Kullanıcıların mesaj göndermesini, gönderilen mesajı güncellemesini ve silmesini sağlar. Yeni mesaj geldiğinde sistem bildirim sesi verir.

5. Personel İşlemleri

5.1 API Metodu:

5.2 POST /personnel

5.3PUT /personnel/{personnelId}

5.4DELETE /personnel/{personnelId}

Açıklama: Personel ekleme, güncelleme ve silme işlemlerini sağlar. Bu işlemler yalnızca yönetici tarafından yapılabilir.
