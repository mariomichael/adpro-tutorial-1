[REFLEKSI]

# Module 1 <br />
1. <br />
Saya merasa pengetahuan saya bertambah banyak setelah mengerjakan exercise 1. Ada beberapa penerapan clean code yang saya lakukan pada tutorial ini. Salah satu penerapan tersebut adalah menggunakan variabel atau nama yang jelas dan menggambarkan apa yang Ia lakukan. Hal ini akan memudahkan kita untuk mengerti tujuan kode tersebut. Selain itu pada tutorial ini juga saya tidak menambah comment yang bertele-tele dan tidak berguna, penggunaannya lebih efisien. Terakhir, saya menggunakan konsep object-oriented programming untuk menghasilkan code yang lebih terstruktur dan mudah dibaca. <br />

2. <br />
Setelah membuat unit test saya merasa lebih tenang. Saya yakin kode yang saya hasilkan benar karena saya selalu melakukan test ulang ketika ada perubahan. Seharusnya dalam satu class ada minimal satu function test untuk setiap method yang ada. Memastikan unit test benar bisa dengan mencoba manual atau mencoba beberapa test-case yang dirasa sudah valid. Menurut saya code coverages tidak menentukan segalanya. Buat apa tinggi tapi tidak berkualitas? Menurut saya kebersihan kodenya jadi terganggu karena jadi seperti ada repetisi kode meskipun itu hanya unit test. <br />

# Module 2 <br />
1. Ada beberapa code quality issues yang saya perbaiki di exercise. Salah satu diantaranya adalah saya menambahkan default permission pada workflows menjadi read only. Selain itu saya juga menambahkan beberapa test yang meningkatkan code coverage. Hal ini akan meningkatkan kualitas kode karena kode yang dibuat akan semakin terjamin. Selain itu saya juga menambahkan function findById beserta tesnya pada ProductRepository untuk memudahkan proses penemuan item dengan ID. Beberapa hal di atas adalah hal yang saya perbaiki dari yang ada sebelumnya.      <br />
2. Ya, menurut saya implementasi saya saat ini memenuhi definisi Continuous Integration and Continuous Deployment (CI/CD). Hal ini dapat diliat dari adanya pengintegrasian beberapa branch ke satu branch utama yaitu branch main. Hal tersebut menegaskan adanya Continuous Integration. Dari sisi Continuous Deployment, seluruh proses deploy diotomasi dengan Koyeb. Dengan penggunaan Koyeb, pekerjaan deployment bisa dijalankan dengan lebih cepat. Berdasarkan beberapa poin di atas, dapat disimpulkan bahwa kode saya telah memenuhi definisi CI/CD. <br />

# Module 3 <br />
1. Saya menerapkan beberapa prinsip pada proyek saya kali ini. Beberapa prinsip tersebut diantaranya:
   * Single Responsibility Project (SRP)
     Saya menerapkan prinsip ini dengan memisahkan CarController dari ProductController agar module ProgramController tetap memegang satu tugas yaitu mengatur aplikasi Product.
   * Open-Closed Principle (OCP)
     Saya menerapkan prinsip ini dengan membuat Car sebagai child dari Product karena mereka memiliki banyak kemiripan.
   * Liskov Substitution Principle (LSP)
   * Interface Segregation Principle (ISP)
   * Ini ditunjukkan pada CarServiceImpl yang menjadi implementasi dari interface Car Sevice
   * Dependency Inversions Principle (DIP)
     Penerapan DIP dilakukan dengan menggunakan interface.
<br />
2. Menurut saya ada beberapa keuntungan menerapkan SOLID. Salah satunya adalah memudahkan pada satu masalah. Jika terdapat masalah di salah satu folder, kita bisa fokus ke bagian dan folder itu. Selain itu prinsip tersebut memudahkan dalam menambahkan fitur. Karena adanya prinsip SOLID, kita tidak perlu fokus menambahkan banyak hal ke berbagai file karena semuanya terfokus di satu titik. Misalnya hanya perlu menambahkan di bagian Car jika ingin improve Car. Selain itu SOLID memudahkan testing karena function yang dilakukan hanya melakukan satu tugas saja.
<br />
3. Menurut saya ada beberapa kekurangan. Misalnya kesulitan memaintain code. Dengan tidak menerapkan SOLID, fokus akan terpecah kek beberapa hal dan tidak fokus di satu titik misalnya modul Car. Selain itu akan sulit melakukan testing. Hal ini dikarenakan satu function bisa melakukan banyak tujuan. Oleh karena itu lebih baik menggunakan SOLID principle.

# Module 4 <br />
1. Menurut saya, alur pengerjaan TDD ini sangat berguna bagi saya untuk membiasakan diri mengikuti standar industri besar. Alur ini mungkin akan memperlambat saya di awal tapi akan mempermudah kinerja saya di akhir nanti. Sesuai dengan prinsip TDD, saya harus membuat test dahulu sebelum membuat code aktualnya. Hal ini melatih saya untuk membuat sesuatu untuk memenuhi target tertentu. Hal tersebut juga melatih saya untuk berpikir dahulu sebelum mengoding. Hal ini karena dengan membuat test dahulu baru membuat kode asli, saya jadi harus mengetahui tujuan kode asli tersebut agar bisa membuat tesnya. Langkah terakhir ditutup dengan refactor yang tentunya sangat berguna untuk mengecek kembali kesalahan atau kekurangan yang belum dicover. Jadi bagi saya TDD flow ini adalah alur yang sangat berguna dalam proses belajar saya. <br />
<br />
2. Menurut saya tes yang saya buat sudah cukup memenuhi kaidah F.I.R.S.T., meskipun ada beberapa tes yang belum memenuhi kaidah tersebut. Menurut saya, tes yang saya buat memiliki kekurangan di area isolation, karena sebenarnya ada beberapa area yang bisa dibuat lebih terisolasi. Selain itu saya agak kurang di bagian reproducibility karena saya belum terlalu mencoba code saya di device lain. Selain kedua aspek itu, aspek speed, self-validation, dan timeliness menurut saya sudah saya penuhi sesuai dengan aspek masing-masing. Meskipun begitu saya menyadari masih banyak yang harus saya pelajari untuk membuat tes yang lebih baik lagi.
