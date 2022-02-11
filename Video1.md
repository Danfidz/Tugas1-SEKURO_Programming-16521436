# Video 1
# Git & Github

- Git dan Github adalah 2 hal yang berbeda yang bisa dipisah dan digabungkan (bisa dipakai terpisah dan berbarengan)
- Git adalah salah satu version control system (VCS).
- VCS perlu dipakai, contoh skenario:
1. Skripsi original yang terus bertambah seperti revisi nya bertambah. Kita kesulitan membuat dan melacak perubahan versi-versi untuk file kita
2. Mau bikin software / website sendiri itu kek source code kan pasti ada di laptop sendiri. Tetapi ketika berkelompok dan mengerjakan semuanya paralel di laptop masing", source codenya ada di laptop masing" juga dan repot ketika harus digabungkan jadi 1. Proses penggabungan ini disebut kolaborasi. Proses ini bisa ditangani oleh VCS
3. Sharing produk ke orang lain
- Perbedaannya dengan GDrive dan Dropbox adalah 2 aplikasi ini didesain bukan untuk mengerjakan source code
- Jadi apa VCS itu:
A. Sebuah sistem yang menyimpan dan mengelola rekaman perubahan dari source code
B. Memungkinkan bekerja berkolaborasi dengan lebih baik karena mengetahui siapa yang melakukan apa dan kapan sebuah perubahan terjadi, serta memungkinkan kita untuk kembali ke keadaan sebelum perubahan (checkout)
- Contoh VCS lainnya ada subversion, mercurial, dan cvs

Git
- Git adalah sebuah vcs yang memungkinkan kita mengelola perubahan file di dalam folder. Folder itu akan disebut repository / repo. 
- Git akan menyimpan riwayat perubahan file menggunakan serangkaian commit. Commit itu spesifik perubahan apa yang disave kek baris mana, dll gitu.
- Ketika kita melihat sebuah commit, akan muncul angka panjang ngak jelas, yang mana itu adalah hash, string panjang yang merupakan penanda untuk setiap commit, sehingga git bisa mengtrack hash ini untuk commit yang mana. Commit juga ada commit message, tanggal dibuat dan siapa pembuatnya

Git Repo
- Dalam 1 repo yang sama, bisa ada branch (suatu commit alternatif yang tidak menganggu alur commit yang utama), contohnya adalah ketika ingin membuat suatu fitur tetapi belum yakin bakal dipake ato ngak, bisa buat branch (kayak copy projeknya gitu), nah nanti kl ternyata dipake, bisa digabungin lagi commitnya itu ke commit utama. Proses penggabungan 2 commit disebut merge

- Proses pembuatan commit, ngemerge, dll bisa dilakukan dalam komputer sendiri (local), asalkan kita install git. 

- Github itu adalah sebuah website, layanan cloud untuk menyimpan & dan mengelola project / repo git. Github itu intinya bisa melakukan hal yang sama seperti di dalam Git tadi, bedanya adalah ini dilakukan secara online. Github adalah sebuah website yang menggunakan git (tapi terpisah dari Git di laptop, jadi ngak perlu install Git di laptop juga bisa). 
- Kl kita install Git di laptop, kita bisa kirim source code, repo, (push) dari Git kita ke Github dan menarik source code, project, dll (pull) dari Github ke Git di laptop kita. Hal yang dipush / dipullnya adalah commit nya. Syarat nya adalah Github ini harus dibikin menjadi remote (sumber dari repo) jadi kek kita bikin repo di Github, lalu reponya diclone sehingga di laptop kita juga ada
- Layanan selain Github, ada Bitbucket, Gitlab

Istilah Git
1. Repo = folder project kita
2. Commit = rekaman / snapshot dari repo kita
3. Hash = penanda unik pada sebuah commit
4. Checkout = berpindah ke sebuah commit
5. Branch = cabang bebas dari sebuah commit
6. Merge = mengabbungkan branch
7. Remote = sumber yang memiliki repo
8. Clone = mengambil repo dari remote
9. Push = Mengirimkan commit ke repo
10. Pull = Mengambil commit dari repo