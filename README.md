# PesawatTempur

| Variabel | Isi |
| -------- | --- |
|**Nama**| Eka Juliyana Rahayu |
|**NIM** | 312310594 |
|**Kelas** | TI.23.A6 |

<p>buat rancangan program sederhana sebuah pesawat tempur yang memiliki data dan fungsi dintaranya :</p>
<p>-warna                  </p>            
<p>-ketinggian             </p>
<p>-kecepatan              </p>
<p>-energi                 </p>
<p>-arah                   </p>

<p>* nyalakanmesin()</p>
<p>* terbang() </p>
<p>* tambahkecepatan()</p>
<p>* belok(arah)</p>
<p>* turun()</p>

## 1. deklarasikan kelas `pesawat tempur`
![Screenshot 2024-09-30 111027](https://github.com/user-attachments/assets/34f3611b-5395-4b40-8f27-8188ed31554a)
<p>Dalam kelas ini, atribut dan metode yang menggambarkan perilaku pesawat tempur akan dituliskan</p>

## 2. atribut pesawat tempur
![Screenshot 2024-09-30 111252](https://github.com/user-attachments/assets/5a0a1255-d4a9-484b-9733-58d300e7e569)
<p>masukan atribut pesawat tempur sesuai yang diperintahkan</p>
<p>pada atribut `warna` digunakan untuk menyimpan warna apa yang kita inginkan pada pesawat tempur dalam bentuk `string` </p>
<p>atribut `ketinggian`  untuk menyimpan ketinggian pesawat dalam meter. ketiggian awal pesawat 0</p>
<p>atribut `kecepatan` menghemat kecepatan pesawat dalam kilometer per jam (km/jam). kecepatan awal 0 </p>
<p>atribut `energi` digunakan untuk menghemmat energi dalam bentuk persentase(%). niali awal 100% yang artinya energi dalam keadaan penuh</p>
<p>atribut `arah` menyimpan kemana arah pesawat</p>
<p>atribut `mesinNyala` untuk mendeskripsikan apakah mesin pesawat dalam keadaan menyala atau tidak. pada awalnya mesin dalam keadaan mati atau `false`</p>

## 3. Konstruktor `pesawat tempur`
![Screenshot 2024-09-30 112658](https://github.com/user-attachments/assets/c7cdefa4-02eb-4593-bc39-5f0c543496a5)
<p>Konstruktor ini digunakan untuk membuat objek pesawat tempur baru.</p>
<p>ketika objek pesawat dibuat maka kita dapat menentukan warna pesawat serta dapat mengisi nilai pada atribut tersebut dengan nilai awal default </p>

## 4. metode `nyalakan mesin`
![Screenshot 2024-09-30 113121](https://github.com/user-attachments/assets/dafd90b2-a5ce-4d63-8267-761d010d7347)
<p>metode ini digunakan untuk menyalakan mesin pesawat</p>

## 5. metode `nyalakan mesin`
![Screenshot 2024-10-01 183642](https://github.com/user-attachments/assets/db0d6763-59ce-4271-b431-5fbe0f15b00f)
<p>metode ini digunakan unntuk menaikkan pesawat ke udara</p>
<p>jika mesin  menyala (true) maka pesawat akan naik 1000 meter dan energi berkurang 100% </p>

## 6. metode `tambah kecepatan`
![Screenshot 2024-10-01 183957](https://github.com/user-attachments/assets/39aff0d3-3ccb-40ad-aa67-b72195bbda53)
<p>metode ini digunakan untuk menambah kecepatan</p>
<p>jika mesin menyala maka kecepatan pesawat bertambah 100 km/jam dan energi berkurang 5%</p>

## 7. metode `kurangi kecepatan`
![Screenshot 2024-10-01 184229](https://github.com/user-attachments/assets/3f5c83f8-6bf8-4b5a-a785-f78a98b3d7c6)
<p>metode ini digunakan untuk mengurangi kecepatan pesawat</p>
<p>jika mesin menyala dan kecepatan lebih dari 0 maka kecepatan akan berkurang 100 km/jam</p>
<p>jika mesin belum menyala atau kecepatan sudah 0 maka pesawat tidak bisa mengurangi kecepatan</p>

## 8. metode `turun`
![Screenshot 2024-10-01 184858](https://github.com/user-attachments/assets/a0fad603-28d1-4e9f-872f-6ffba49a512b)
<p>metode ini digunakan untuk menurunkan pesawat</p>
<p>jika mesin menyala atau ketinggian lebih besar dari 0 maka pesawat akan turun sejauh 1000 meter</p>

## 9.  metode `ubah arah`
![Screenshot 2024-10-01 184912](https://github.com/user-attachments/assets/bba1382f-519e-4f40-9090-566db3999ed1)
<p>metode ini digunakan untuk mengubah kemana arah pesawat yang diinginkan atau arah baru yang di simpan di atribut arah</p>

## 10. metode `status pesawat`
![Screenshot 2024-10-01 185615](https://github.com/user-attachments/assets/1d6413a2-2048-4f6e-8976-50ebce90df1b)
<p>metode ini digunakan untuk menampilkan status terkini pesawat seperti warna, ketinggian, kecepatan, energi, arah, mesin menyala atau mati</p>

## 11. metode `main`
![Screenshot 2024-10-01 185626](https://github.com/user-attachments/assets/6619b7f9-83c6-434f-abf2-4827bd765e50)
<p>metode ini digunakan untuk kita membuat objek pesawat baru, misalnya warna : abu-abu</p>
<p>Mesin dinyalakan, pesawat terbang, kecepatan bertambah, berbelok ke arah "Barat", mengurangi kecepatan, dan turun.
maka status akhir akan ditampilkan</p>

## Kode keseluruhan
![Screenshot 2024-09-28 213802](https://github.com/user-attachments/assets/2189d5af-2a9a-4a45-9e8f-30505ffd1533)
![Screenshot 2024-09-28 213818](https://github.com/user-attachments/assets/483f37f1-b763-4b6f-ba8e-79bf0831f71d)
![Screenshot 2024-09-28 213834](https://github.com/user-attachments/assets/6cd96dfd-ed2d-4009-b081-caa92e12eed9)
![Screenshot 2024-09-28 213845](https://github.com/user-attachments/assets/03786697-e9a2-4b0d-939f-c6733acfa6af)
![Screenshot 2024-09-28 213901](https://github.com/user-attachments/assets/a9b5be76-dfb3-4f6a-a381-ebe57fd8b9d4)



