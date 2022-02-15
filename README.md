# Shift-Chiper-Kriptografi-Besic-CyberSecurity
Shift Chiper adalah jenis kriptografi menggunakan teknik perhitungan jumlah index dengan perbandingan jumlah pergeseran index yaitu kanan dan kiri.

sebagai gambaran 0:
      var dekripsi  = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ';
      var enkripsi  = 'ZYXWVUTSRQPONMLKJIHGFEDCBAZYXWVUTSRQPONMLKJIHGFEDCBA';
      
pergeseran kanan 1:
      var dekripsi  = .'ABCDEFGHIJKLMNOPQRSTUVWXYZ';
      var enkripsi  = 'ZYXWVUTSRQPONMLKJIHGFEDCBAZYXWVUTSRQPONMLKJIHGFEDCBA';
      
      ==>disini posisi 'A' sejajar dengan 'Y', dan 'Z' sejajar dengan 'Z';
      
pergeseran kiri 1:
      var dekripsi  =                          'ABCDEFGHIJKLMNOPQRSTUVWXYZ'.;
      var enkripsi  = 'ZYXWVUTSRQPONMLKJIHGFEDCBAZYXWVUTSRQPONMLKJIHGFEDCBA';
      
      ==>disini posisi 'A' sejajar dengan 'A', dan 'Z' sejajar dengan 'B';
