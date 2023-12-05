# tugas minggu ke-11

# latihan
    print("Nama : Siti Nurhasanah")
    print("NIM  : 312310559")
    print("=========================")

    import math
    def a(x):
        return x**2
        a = lambda x: x**2, a
    print(a(2))

    def b(x, y):
        return math.sqrt(x**2 + y**2)
        b = lambda x, y: x**2 + y**2, b
    print(b(2, 4))

    def c(*args):
        return sum(args) / len(args)
        c = lambda*args: sum(args) / len(args)
    print(c(10, 50))

    def d(s):
        return "".join(set(s))
        d = lambda s: "".join(set(s))
    print(d("Siti"))

Input
![Screenshot_125](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/914f70fe-60b7-4db7-b409-7d7ad798077b)

Outpout
![Screenshot_127](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/717b4ffd-820e-49a2-903b-f289db2afeaf)

# Praktikum
Program atau input
![Screenshot_142](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/5ffbbbe9-655a-4058-8513-818feac6623d)
![Screenshot_143](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/3ebf2e6b-70ef-4b27-b1f0-660bb52700b0)
![Screenshot_144](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/91fc6cc3-d49e-4927-8659-0c2e07029f48)
![Screenshot_145](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/99f383ba-dc20-4721-87cb-e96478ac2ac9)
![Screenshot_146](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/53299fad-e6d1-4933-b7e2-025c449686ac)

output
•   Tampilan awal
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/ce286b15-21a0-4ac5-bdcc-10def17bf628)

•	menambahkan data
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/c2690dac-c732-40d3-970a-52aa5c4d0c4c)
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/59fa4da8-0b20-48ed-a28a-b46a816bf094)
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/74b600f5-d37e-4fca-86b7-819e2b3a683d)

•	menampilkan data
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/aec906a5-5629-4b32-b5c1-042bcd07a3fe)
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/cb02d037-cbb2-43b6-a800-a52129f5a9ee)

•	mengubah data
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/4b9883e0-dec9-4a31-9092-26c41e2ce5bf)

•	menghapus data
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/de8ba674-eca5-4da5-b808-9cc50867e5fa)
![image](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/1ce15ec0-16e8-4308-b5d6-37505ed6fddc)

# Penjelasan Praktikum
1.	Definisikan dictionary terlebih dahulu data = {}.
2.	Membuat fungsi
•	Fungsi tampilkan(), untuk menambahkan data def tampilkan()
•	Fungsi tambah(), untuk menampilkan data def tambah()
•	Fungsi hapus(nama), untuk menghapus nama pada data def hapus(nama)
•	Fungsi ubah(nama), untuk mengubah nama pada data def ubah(nama)
3.	Menggunakan Perulangan while True: dapat diartikan perulangan akan terus mengulang jika inputan benar dan masuk kedalam proses jika tidak maka perulangan berhenti atau lanjut ke proses selanjutnya. Gunakan statement if untuk memproses perintah yang di inginkan sesuai inputan.
4.	Untuk menambahkan data pilih "[1] Tambah" gunakan fungsi if gunakan perintah "1", lalu masukan nama, nim, tugas, uts, uas, nilaiakhir, nilai akhir didapat dari = ((tugas)*30/100 + (uts)*35/100 + (uas)*35/100.
5.	Lalu jika ingin memilih "[2] Lihat" gunakan fungsi 'elif' dan gunakan fungsi 'for x in data.items():' untuk melihat data pada tabel data yang kita inputkan, dengan perintah "2". Jika data tidak terdaftar maka akan tampil "TIDAK ADA DATA" atau = 0.
6.	Lalu untuk menampilan pilihan "[3] Ubah" gunakan fungsi 'elif' kemudian gunakan fungsi 'if nama in data.keys():' kemudian input nama, nim, nilai tugas, nilai uts, nilai uas untuk mengubah data nama kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita ingin ubah tidak ada.
7.	Untuk menghapus data pilih "[4] Hapus" gunakan fungsi 'elif' kemudian gunakan fungsi 'if nama in data.keys():' kemudian fungsi 'del.data[nama] jika nama yang kita hapus tidak ada dalam tabel maka gunakan fungsi 'else' untuk menampilkan "TIDAK ADA DATA".
8.	Untuk keluar maka gunakan fungsi else dan exit() atau gunakan perintah [5] Keluar.
9.	Selesai.

# Flowchart
![Screenshot_147](https://github.com/hanur1303/tugaspraktikumm7/assets/148194701/9221fbba-47b6-49fc-a836-b41e36bea093)


flowchart




