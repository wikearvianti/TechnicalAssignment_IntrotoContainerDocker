1. Jelaskan apa yang dimaksud dengan container pada docker !
Container adalah sebuah wadah ringan seperti cloud yang berisi semua keperluan untuk menjalankan sebuah aplikasi. Melalui Docker ini seorang pengembang dapat berbagi container saat bekerja membangun aplikasi. Container terdiri dari keseluruhan runtime environment: aplikasi, dependency, library, binary, serta konfigurasi file yang dibutuhkan untuk menjalankannya.

2. Jelaskan apa perbedaan antara konsep container dengan virtual machine !
Virtual machine (VM) adalah sebuah emulasi dari sebuah sistem komputer. Secara sederhana, virtual machine membuat kita bisa membagi resource hardware dari satu hardware fisik menjadi beberapa sistem komputer. Berbeda dari VM, container adalah sebuah virtualisasi OS yang dapat membungkus suatu aplikasi beserta dependency dan environment-nya. Setiap container ini memiliki process yang terisolir sehingga tidak mengganggu host OS ataupun container yang lain. Prinsip container ini mirip dengan kontainer yang ada di kapal kargo di mana kapal kargo tersebut diibaratkan sebagai sistem komputer. Jika dibandingkan dengan VM, secara pengaturan kontainer lebih mudah. Hal ini disebabkan karena konsep berbagi resource hardware dari container lebih fleksibel bila dibandingkan VM. 

3. Apa yang dimaksud dengan docker file ?
Dockerfile adalah file teks yang berisi semua perintah yang bisa dijalankan user pada baris perintah untuk membuat image. Ini mencakup semua instruksi yang diperlukan oleh docker untuk membangun image. Tidak semua kata kunci diperlukan agar Dockerfile berfungsi. Contohnya, hanya akan menggunakan FROM, MAINTAINER, dan RUN.

4. Apa yang dimaksud dengan docker registery ?
Registry adalah sebuah repository atau sebuah penyimpanan image terpusat, kasarnya image yang sudah dibuat oleh orang orang atau mungkin kalian ikut membuat sebuah image, maka Registry adalah sebuah tempat yang tepat untuk menyimpan images. Docker registry bisa dihost oleh pihak ketiga sebagai pribadi ataupun publik. Dengan registry, commit workflow menjadi lebih mudah tanpa harus dilakukan manual.

5. Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung !
Cara menjalankan lebih dari 2 container secara bersamaan dan saling terhubung yaitu dengan docker compose, alat konfigurasi yang bekerja dalam satu file YAML. Perintahnya terdiri dari start all service, install compose using pip, stop all services, version checking, scalling service, run file, dan list process.