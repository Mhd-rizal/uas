# uas

login.php

berisi form login dengan session start() untuk memuali sesi login

uas.php

disisipkan fungsi validasi cek login,jika belom login tetapi langsung di rect akses ke indext.php,input php,edit.php, maka akses ditolak dan lalu muncul peringatan di lanjut dengan redirect ke lagin page otomatis pada label data pasien covid terdapat pilihan  edit, delet,input, dan logout lanjut ke tombol input(input.php)

input.php

di sisipkan fungsi validai cek login
berisi form yang dimana nama,alamat,provinsi,email,Nohp,keahlian tersimpan kedatabase relawan table covid
sedangkan dropdown provinsi berisi 34 provinsi di indonesia yang tersimpan dan di ambil dari database relawan relawan table provinsi yang selanjutnya teresimpan di table covid
ada tombol add (submit) untuk menyimpan dan reset untuk menghapus semua inputan, jika sudah di add maka otomatis teralihkan ke index.php atau tampilan data relawwan
fungsi input.php tersinmpan di proses.php

edit.php

disisipkan fungsi validasi cek login berisi form ang dimana nama ,alamat,provinsi,emailnohp,keahlian yang diambil dan disimpan kembali ke database relawan table covid
sedangkan dropdpwn provinsi berisi 34 provinsi di indonesia yang tersimpan dan diambil dari database table provinsi yang selanjutnya disimpan ke table covid 
ada tombol add untuk menyimpan fungi edit tersimpan di prosesedit.php

delete.php

didimpan fungsi validasi cek login fungsi delet dari database berdasarka ID yang kita pilih
