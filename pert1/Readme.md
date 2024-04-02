## COMMAND DASAR LINUX

## Membuat Folder baru dalam sistem file (mkdir).
mkdir = Adalah perintah untuk membuat sebuah folder. Sebagai contoh perintahnya adalah: mkdir (nama folder)
<p>cd    = akses membuka folder, contoh foldernya adalah: cd (nama folder yang telah dibuat)</p>
<p>ls    = menampilkan daftar file didalam sebuah folder. contoh perintahnya bisa langsung ketik saja ls.</p>

langkah awal yang kita lakukan adalah membuat folder yang nantinya akan dipakai untuk melakukan perintah. berikut adalah beberapa langkah yang akan dilakukan

<p>langkah langkah membuatnya:</p>
<p>1. buka terminal</p>
<p>2. ketik mkdir (nama folde, gak usah pake tanda kurung) enter</p>
<p>3. ketik ls enter</p>
<p>4. ketik cd (nama folder yang telah dibuat, gak usah pake tanda kurung) enter (untuk membuka akses folder yang telah dibuat)</p>
<p>5. ketik ls enter</p>
<p>6. ketik code . enter (untuk masuk ke vscode)</p>

## Membuat isi folder
setelah membuat isi folder, selanjutnya membuat isi folder. untuk membuat isi folder tidak jauh berbeda dengan membuat folder. setelahnya buat file file yang diperlukan di dalam folder tersebut. setelahnya isi file sesuai kebutuhan. 
<p>langkah langkah membuatnya:</p>
<p>1. buka terminal</p>
<p>2. ketik cd (nama folder yang telah dibuat, gak usah pake tanda kurung) enter</p>
<p>3. ketik ls enter</p>
<p>4. ketik mkdir (nama isi folder yang akan dibuat, gak usah pake tanda kurung) enter</p>
<p>5. ketik ls enter</p>
<p>6. ketik code . (untuk membuka vscode) enter</p>

## Cara ngepush ke github
langkah untuk ngepush pembaruan di github yang repositorinya telah dibuat:
<p>buka terminal bisa langsung di vscode atau terminal lainnya.</p>
<p> 1. jika terminal dari vscode berikut langkahnya:</p>
<p> karena menggunakan terminal dari vscode maka langsung ketikkan git add . lalu enter ketik lagi git commit -m "nama_folder" enterr dan ketik git push -u origin main  setelah itu cek github sudah terpush atau belum.</p>
<p> 2. jika menggunakan terminal dari ubuntu langkahnya sebagai berikut:</p>
<p> - ketik cd (nama folder, gak usah pake tanda kurung) (lalu enter)</p>
<p> - ketik ls (lalu enter)</p>
<p> - ketik cd (isi folder, gak usah pake tanda kurung) (lalu enter)</p>
<p> - ketik ls (lalu enter)</p>
<p> - ketik git add . (lalu enter)</p>
<p> - ketik git commit -m "nama_folder" (lalu enter)</p>
<p> - ketik git push -u origin main (lalu enter)</p>
<p>setelah itu dicek kembali di github apakah sudah terpush atau belum.</p>

## 
<p>langkah untuk ngepush dan membuat repositori baru di github</p>
<p>jika menggunakan terminal dari ubuntu langkahnya sebagai berikut:</p>
<p> - ketik cd (nama folder, gak usah pake tanda kurung) (lalu enter)</p>
<p> - ketik ls (lalu enter)</p>
<p> - ketik cd (isi folder, gak usah pake tanda kurung) (lalu enter)</p>
<p> - ketik ls (lalu enter)</p>
<p> - ketik git init</p>
<p> - ketik git add . (lalu enter)</p>
<p> - ketik git commit -m "nama_folder" (lalu enter)</p>
<p> - ketik git branch -M main  (lalu enter)</p>
<p> - ketik git remote (link ssh, gak usah pake tanda kurung langsung linknya aja) ssh ambil di github yang akan digunakan</p>
<p> - ketik git push -u origin main (lalu enter)</p>
<p>setelah itu dicek kembali di github apakah sudah terpush atau belum.</p>
<p> * git init = Menginisialisasi repositori Git baru di direktori saat ini.</p>
<p> * git add . = Menambahkan semua perubahan yang belum di-track ke staging area.</p>
<p> * git commit -m "nama_folder" = Membuat commit dengan pesan "nama_foler" dari perubahan-perubahan yang ada di staging area.</p>
<p> * git branch -M main =  Mengganti nama branch dari "master" menjadi "main" (ini adalah praktik yang semakin umum dilakukan untuk menghindari konotasi yang mungkin tidak diinginkan dari istilah "master").</p>
<p> * git remote (link ssh, gak usah pake tanda kurung langsung linknya aja) = Menambahkan remote repository dengan URL SSH yang diberikan oleh GitHub. Ini memungkinkan Git untuk berkomunikasi dengan repositori jarak jauh.</p>
<p> * git push -u origin main  = Mendorong (push) perubahan lokal ke repositori jarak jauh di branch "main", dan menetapkan branch lokal "main" untuk melacak branch "main" di repositori jarak jauh ("origin"). Opțiune -u menetapkan branch saat ini sebagai branch upstream, yang memungkinkan Anda menggunakan perintah git push tanpa argumen di masa mendatang.</p>




## Command dasar linux lainnya
cd .. =  digunakan untuk berpindah satu level ke atas dalam struktur direktori
<p>nano  = digunakan untuk mengedit berkas konfigurasi sistem, skrip, atau berkas teks lainnya di lingkungan server atau pengembangan perangkat lunak. contoh (nano .env)</p> 
<p>code . = untuk membuka folder di vscode. (lansung ketik di terminal setelah membuka folder yang diinginkan)</p>
<p>rm    = digunakan untuk menghapus berkas atau direktori di sistem Unix/Linux</p>
<p>mv    = untuk memindahkan berkas atau direktori dari satu lokasi ke lokasi lainnya, contohnya (mv (nama folder) (nama folder)).</p>
<p>chmod = untuk memberikan izin (permissions) dari berkas atau direktori di sistem Unix/Linux. contohnya, (chmod 777 -R storage/*)</p>
<p>touch = digunakan untuk membuat berkas kosong baru di sistem Unix/Linux.</p>
<p>g++ ./(nama file) = untuk running </p>
<p>git branch -M main = digunakan untuk mengubah nama branch default dari "master" ke "main".</p>
<p>cat  = Untuk menampilkan isi file.</p>
<p>pwd  = Untuk menampilkan direktori saat ini.</p>
<p>cp  =  Untuk menyalin file dan direktori.</p>
<p>grep: Untuk mencari teks dalam file.</p>
<p>chown: Untuk mengubah kepemilikan file atau direktori.</p>
<p>apt-get (atau apt): Untuk mengelola paket-paket pada distribusi Linux yang menggunakan sistem manajemen paket Debian.</p>
<p>yum: Untuk mengelola paket-paket pada distribusi Linux yang menggunakan sistem manajemen paket RPM.</p>
<p>git clone "link yang mau di clone"  = untuk membuat salinan lengkap dari repositori Git yang sudah ada. Ini berguna saat Anda ingin bekerja dengan repositori yang sudah ada secara lokal di komputer Anda.</p>


## PERHATIAN
setiap mengetikan kode atau syntax diharuskan benar benar teliti. karena jika tidak akan menimbulkan error atau program tidak akan jalan sesuai dengan keinginan yang kita mau.