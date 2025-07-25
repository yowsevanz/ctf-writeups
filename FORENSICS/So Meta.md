# So Meta
### picoctf2019

### Deskripsi
Find the flag in this [picture](https://jupiter.challenges.picoctf.org/static/916b07b4c87062c165ace1d3d31ef655/pico_img.png)

### Hint 
1. What does meta mean in the context of files?
2. Ever heard of metadata?

### Step by step

mari kita jawab hint yang diberikan terlebih dahulu.

metadata : data tentang data atau informasi dalam sebuah data/file

Kalau file adalah isi utama, maka metadata adalah informasi yang menjelaskan: File ini berisi apa? Siapa yang membuatnya? Kapan dibuat?
Format, ukuran, hak akses, dll.

biasanya using exiftool untuk menampilkan metadata

untuk menyelesaikannya langsung saja buka webshell picoctf 

1. simpan file terlebih dahulu
   
format: wget link
   ![save](https://github.com/yowsevanz/images/blob/main/So%20Meta/save.png)
2. gunakan exiftool untuk menampilkan metadata
   ![metadata](https://github.com/yowsevanz/images/blob/main/So%20Meta/metadata_someta.png)

   lihat dibagian Artist, ada flag!

   ### flag : picoCTF{s0_m3ta_d8944929}

   
