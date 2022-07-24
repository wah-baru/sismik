# Sismik
Repo ini berisi kode sumber dari program yang dibuat selama mengikuti kelas Sismik.
Perangkat target yang digunakan adalah STM32 Bluepill (STM32F103C8T6)
Ada dua folder, yang masing-masing menyimpan kode dan file untuk target yang berbeda.
Yang pertama adalah kode untuk perangkat yang diemulasikan* dalam Proteus, sedangkan yang kedua adalah kode untuk perangkat sesungguhnya.

## Folder fail
Berisi file dan _workspace_ Proteus. Disini perangkat keras diemulasikan dalam Proteus. Hanya perlu menyiapkan Hex File untuk diisi kedalam perangkat yang diemulasikan*. 

## Folder kel10-hardware
Berisi file dan _workspace_ STM32Cube IDE, perangkat lunak serbaguna yang disediakan oleh STMicroelectronics. Berisi kode inti untuk STM32 Bluepill. 

### Kenapa ada dua folder?
Awalnya kami mencoba untuk mengembangkan kode untuk diisikan langsung kedalam perangkat yang diemulasikan* dalam Proteus. Sayangnya alat yang kami buat tidak beroperasi sebagaimana yang diharapkan. Oleh karena itu kami pun menyiapkan perangkat aslinya.
Dari kegagalan itu kita mengetahui kalau kelemahan perangkat yang diemulasi* adalah perangkat ini tidak nyata, jika berurusan dengan timer maka perangkat tidak dapat berfungsi sebagaimana mestinya.
Setelah menyiapkan perangkat aslinya dan beberapa alat dan bahan tambahan**, alat yang kami buat berfungsi sebagaimana yang diharapkan.

*sebenarnya saya sendiri masih bingung kata apa yang cocok, mohon sarannya heheh
**karena rancangan alat dibuat seluruhnya didalam Proteus, kami menyiapkan alat dan bahan aslinya (_real hardware_). bakalan repot nanti kalo beli stm32 buat gerakin servo yang ada didalam proteus.
