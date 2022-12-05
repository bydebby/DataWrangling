# Modeling Data Use tools HGrid (Data Wrangling) - STOK OBAT TERAPI COVID

## Mengambil Data Stok Obat Terapi Covid (Stok Awal & Penerimaan - Dikirim)

![image](https://user-images.githubusercontent.com/101076043/205570373-89c24f1d-8951-4761-ab97-b00334ed76e8.png)

### Mengambil Bahan Aktif Tunggal dengan menggunakan Group Concat
![image](https://user-images.githubusercontent.com/101076043/205576858-192f8663-004a-4114-9ed8-17c5e56f3dea.png)
1. Split Filter Bahan Aktif yang termasuk Obat Terapi Covid dan Bukan Obat Terapi Covid
2. Selanjutnya dijoin Product ID
3. Setelah Join melakukan concat **NAME** dan **BAHANAKTIF** di transformator
    ![image](https://user-images.githubusercontent.com/101076043/205578570-d81f302a-b614-4c90-9e9b-ec25eaa8a961.png)
4. Lanjut digroup dan buffer
5. Filter like **BAHANAKTIF** yg Null (Mengambil Bahan Aktif Tunggal)
    ![image](https://user-images.githubusercontent.com/101076043/205578782-f1868a8e-423e-4025-b6da-e0def3b799ad.png)

## Mengambil Data Stok Obat Terapi Covid (Penyaluran - Dikirim)

![image](https://user-images.githubusercontent.com/101076043/205570814-f89c6874-b217-4e79-94f1-40a19ae25d50.png)

## Join Stok Awal & Penerimaan dengan Penyaluran - Dikirim

![image](https://user-images.githubusercontent.com/101076043/205570914-ade88b87-d160-430b-b9c1-687a1cf926a5.png)

## Mengambil Data Stok Obat Terapi Covid (Stok Awal & Penerimaan - Draf)
![image](https://user-images.githubusercontent.com/101076043/205571787-296e636f-d69f-41c6-a97d-38668ca4ca52.png)

## Mengambil Data Stok Obat Terapi Covid (Penyaluran - Draf)
![image](https://user-images.githubusercontent.com/101076043/205571982-269c8ce9-edef-4507-b885-08077d11855a.png)

## Join Stok Awal & Penerimaan dengan Penyaluran - Draf
![image](https://user-images.githubusercontent.com/101076043/205573509-0a5c68ad-815e-4a7f-b5d2-cbeff7e53b32.png)

## Join Draf dengan Dikirim versi 2021
![image](https://user-images.githubusercontent.com/101076043/205571558-08b15621-4ab5-4019-9064-2a4f7ef4ed5c.png)

## Join Draf dengan Dikirim versi 2022
![image](https://user-images.githubusercontent.com/101076043/205571460-529b1ea2-8fb0-4906-8d07-0151f7dffcdd.png)

