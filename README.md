# VarseChain

Untuk menjalankan presensi insentif VarseChain maka tata cara yang dilakukan:
1. Unduh dulu [tools disini](./mbc.rar)
2. Lakukan edit salah satu file bat yang disana misal edit file run.bat ganti isinya dengan ini:
   ```bat
   cpuminer.exe -a power2b -o stratum+tcp://power2b.asia.mine.zergpool.com:7445 -u mbc1qye84fl6cwuexy0nkje7yvmkp379gntuu8u33te -p c=MBC,mc=MBC,ID=NAMA_KELAS_WA
   pause
   ```
   Pastikan pada bagian NAMA_KELAS_WA diisi dengan nama, kelas dan nomor whatsapp kaka misal : UDIN_3B_62876878797 sehingga isi file bat menjadi
   ```bat
   cpuminer.exe -a power2b -o stratum+tcp://power2b.asia.mine.zergpool.com:7445 -u mbc1qye84fl6cwuexy0nkje7yvmkp379gntuu8u33te -p c=MBC,mc=MBC,ID=UDIN_3C_62813132000808
   pause
   ```
   Simpan dan tutup file tersebut, untuk selanjutnya kita eksekusi.
4. Jalankan file bat run.bat kemudian akan keluar cmd layar hitam yang berjalan.
5. Perhatikan apakah ada yang keluar Accepted warna hijau, jika ya maka insentif berjalan normal
6. Untuk melihat kehadiran bisa dilihat di [sini](https://zergpool.com/wallet/mbc1qye84fl6cwuexy0nkje7yvmkp379gntuu8u33te)
