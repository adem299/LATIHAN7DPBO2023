# LP7C2DPBO2023
Saya Ade Mulyana NIM 2108799 mengerjakan soal LP7 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Desain Program
Program ini terdiri dari beberapa class:
- Synchronization (main class)
- Game (main program)
- GameInterface (class interface render, loop)
- GameObject (implements GameInterface)
- Display (show program in jframe)
- Handler (implements GameObject)
- Controller (implements KeyListener<class default java>)
- Player (extends GameObject)
- Target (extends GameObject)

Program ini juga terdapat package assets yang menyimpan background image.

# Alur program
User dapat mengunakan key `W` `A` `S` `D` atau &uarr;  &larr; &darr; &rarr; untuk menggerakan object player.

# Deskripsi program
1. Ketika player pertama kali bergerak ke arah mana saja score +1, ketika player bergerak lagi ke arah yang sama seperti sebelumnya score tidak bertambah, tetapi jika sebelumnya player sudah bergerak kearah lain dan bergerak ke arah yang sama seperti yang awal maka score tetap bertambah +1.
2. Ketika player menyentuh target (object kotak berwarna kuning) maka TouchScore +1 dan object target tersebut akan hilang, object target baru akan muncul lagi di random position.
3. Kecepatan/Velocity player bergerak pada program ini di set 1 untuk ke segala arah.

# Demo
https://user-images.githubusercontent.com/100661834/233989125-f7878b28-3da5-4f3c-be93-cc9a142357c1.mp4
