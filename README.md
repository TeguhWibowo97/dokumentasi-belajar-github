
Cara upload file ke github :
- klik kanan folder yg akan di upload
- pilih gitbash
- git init
- git add * // untuk menambahkan semua file yg ada di folder
- git remote add origin https://github kita // agar file bisa di upload ke repository github kita
- git status // utk melihat status perubahan pada file project kita
- git commit -m "first upload"
- git pull origin master // untuk meng import file di github ke folder kita
- git push origin master // untuk upload isi folder kita ke github
- Jika nge push project LARAVEL biasanya folder vendor tidak ke upload, maka pake cara ( git add -f vendor )
- git remote set-url origin https://github.com/TeguhWibowo97/adzira.git (jika terjadi eror dan tidak bisa push / upload)

- rm -rf .git // untuk hapus temporary di folder kita yg terhubung ke github
- git rm -f namafile //utk menghapus file


Cara Cloning Project LARAVEL
- git init
- git remote add origin https://link
- git pull origin master
- Pada halaman htdocs buka folder project tersebut di cmd
- ketik ( copy .env.example .env)
- php artisan key:generate
- php artisan migrate
- php artisan serve
