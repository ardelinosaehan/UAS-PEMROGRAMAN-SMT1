# UAS-PEMOGRAMAN-SMT1

# penjelasan
<br>
<h5>Pada folder model dengan nama file daftar_nilai berisi modul untuk tambah data,hapus data,ubah data ,dan cari data,sintaksnya sebagai berikut </h5>
<img src="daftar.png">
<br>
Pada file main.py berisi daftar pilihan menu dengan sintaks sebagai berikut:
<br>
<img style="width:50%" src="menu.png">

pada menu pertama terdapat fitur tambah data dengan output seperti gambar berikut:
<br>
<img src="tambahdata.png">

<br>
<br>
 Pada menu pertama terdapat fitur tambah data dengan sintaks berikut :

``` python

fitur = [{'1': 'TAMBAH DATA',
          '2': 'LIHAT DATA',
          '3': 'HAPUS DATA',
          '4': 'UBAH DATA',
          '0': 'KELUAR'}]


def Main():
    global fitur  #mengubah lingkup variabel fitur yang tadinya local menjadi global
    for key, value in fitur[0].items():
        print(f'{key} {value.title()}')
    print('SELAMAT DATANG DI DAFTAR MAHASISWA')
    menu = str(input('Pilih Menu Anda :'))
    while menu != '0': #jika si user menginput tidak sama dengan 0 maka program akan menjalan fungsi kondisi selanjutnya
        if menu == '0':
            break
        elif menu == '1':
            Cetak()  #akan menampilkan fitur tambah data
   
   ```
    
            

<img src="lihatdata.png">
menu ke-tiga fitur Hapus Data dengan hasil output sebagai berikut
<br>
<img src="ubahdata.png">
