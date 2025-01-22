# The Concept:

![image](https://github.com/user-attachments/assets/e69eec4e-c6ac-41c7-93d5-29c219f0c5dd)

JADI:
- sumbu y (yg lurus keatas) menandakan keanggotaan. 0 artinya bukan anggota, 1 artinya anggota
- sumbu x (yg datar) menandakan apa yg mau kita tentuin, dlm case gambar: usia
- semakin tinggi titik, semakin dia deket ke 1; artinya dia semakin muda (karna di graph ini, dibuat garis biru = muda)
- semakin rendah, semakin tua
- ==> semakin deket ke 1; semakin bener statement itu. semakin deket ke 0; semakin salah statementnya

yh drpd fucking ribet ini aj lgsg:

# **Contoh soal and pengerjaan kiddos**
![image](https://github.com/user-attachments/assets/e3274c19-be52-4ec0-a1b5-495eb3f94c2e)

From this soal, we can conclude:
- Permintaan tersedikit per hari: 1000
- Permintaan terbanyak: 5000
- Persediaan terbanyak: 600
- Persediaan tersedikit: 100
- Produksi terbanyak: 7000
- Produksi tersedikit: 2000
- Dan peraturan2 di soal, y baca lah jir malas gw ketik ulang
- **Jika permintaan 4000, persediaan 300, berapa yang hrs diproduksi?**

### **Step 1: gambar grafik**
**Grafik Permintaan**
- Permintaan bisa semakin naik atau turun

![image](https://github.com/user-attachments/assets/7767b898-2a86-4c52-870b-021cadcfb3a4)

- Semakin garis biru(grafik permintaan turun) ke kanan; semakin permintaan **_TIDAK_** turun (makanya dia makin deket ke angka 5000)
- Semakin garis hijau(grafik permintaan naik) ke kanan, semakin permintaan **_TIDAK_** naik (makanya dia semakin deket ke angka 1000)
- Grafik keduanya mulai di titik 1000 dan 5000 karena udh batas teratas dan terbawah dr soal
- ^ alias gabisa lebih atau kurang dari itu.

### **Membuat functions (rumus2)**
![image](https://github.com/user-attachments/assets/ee78e5d4-a67b-4ea1-91f5-1ad4ae0a5b9f)

- Mturun[x] itu hrsnya μ yg artinya keanggotaan grafik turun untuk x. sisanya u pada smart ppl u can think
- Baris pertama artinya keanggotaan = 1, jika x lebih kecil sama dgn 1000 -> artinya permintaan TURUN
- keanggotaan = (yg di gambar gw mls ngetik ulang baris 2), jika x diantara 1000 dan 5000
- keanggotaan = 0, jika x lebih besar dari 5000 -> artinya permintaan TIDAK TURUN

![image](https://github.com/user-attachments/assets/49597da6-0387-4e75-96ac-51c79cda861c)

- the rest u understand la

### sabar, dapet rumus2 itu gimana anjg?
_gini_

![image](https://github.com/user-attachments/assets/92b25f36-d70c-402a-9e82-653618d89386)

- untuk grafik turun = batas bawah dikurang x
- X apaann anjgg? X itu titik yang akan ditanya, dlm case soal kita, permintaan 4000 yg ditanya. so x nya disini 4000
- di contoh itu angkanya beda sm yg soal kita ya.

### **Ok, now lanjut ke grafik persediaan dan produksi (dpt dr mana?? soal jing)**

![image](https://github.com/user-attachments/assets/7e5f6cc0-2a27-4044-9ae5-e78846626619)
_ini banyak yg tbtb dari y sma z tbtb jadi x itu TYPO ya. hrsnya tetep ikut_

### Now, pengerjaan hitung2 nya:
Soal minta **Jika permintaan 4000, persediaan 300, berapa yang hrs diproduksi?**. Maka, kita pakai rumus2 μTurun, μNaik, μSedikit(persediaan), μBanyak(persediaan). Jadi, rumus2 dan grafik produksi gausah dipake dulu.

![image](https://github.com/user-attachments/assets/f9aa9502-f7f4-4c1e-badb-be82a54db5b1)

And now, refer back to rules di soal:

![image](https://github.com/user-attachments/assets/7bb58380-bcf3-4663-9f52-436881b202c4)

[R1] Permintaan Turun dan Persediaan Banyak = Produksi Berkurang
- 0,25 ; 0,4 -> pilih yang terkecil
- =0,25
- Now, masukin ke rumus Produksi tadi
- ![image](https://github.com/user-attachments/assets/1a4e3030-7798-4576-9b64-240367426237)

[R2] Permintaan Turun dan Persediaan Sedikit = Produksi Berkurang
- 0,25 ; 0,6 -> pilih yang terkecil
- =0,25
- ![image](https://github.com/user-attachments/assets/0382217f-0a00-4d30-8b35-2c86c5be2bb3)


[R3] Permintaan Naik dan Persediaan Banyak = Produksi Bertambah
- 0,75 ; 0,4 -> pilih yang terkecil
- =0,4
- ![image](https://github.com/user-attachments/assets/cecfc685-c82f-4c02-81d7-dfed6d591e1d)


[R4] Permintaan Naik dan Persediaan Sedikit = Produksi Bertambah
- 0,75 ; 0,6 -> pilih yang terkecil
- =0,6
- ![image](https://github.com/user-attachments/assets/43d71d04-e98e-4df0-98a9-02d0e2d3a9f9)

### **Last, Defuzzifikasi**
![image](https://github.com/user-attachments/assets/e145a5fc-156d-4cca-a449-1804dbf8a972)

_What tf does that mean bro?_

- Angka2 per rule yg td kita pilih(yg pilih terkecil)
- Dikali hasil Zn yg pake rumus produksi (yg td diatas dihitung tiap R)
- Hitung utk semuanya, dijumlah.
- Dibagi angka2 "terkecil" tadi yg dijumlahkan
- Hasilnya adalah jawabannya.

### _**Jadi, jumlah makanan kaleng jenis ABC yang harus diproduksi adalah 4983**_

