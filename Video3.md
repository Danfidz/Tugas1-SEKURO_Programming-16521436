# Video 3
# Branch

- Branching adalah membuat Git Branch, di mana kita membuat suatu snapshot tanpa menganggu jalur utama (Master Branch) yang biasanya berguna ketika kita sedang membuat suatu fitur experimental. Dalam 1 repo, kita bisa membuat beberapa branch.
- Cara membuat branch:
1. Mengedit file, lalu commit nya itu pilih "create a new branch"
2. Di halaman repository, klik "branch: master" lalu ketik nama branch yang diinginkan (ex: rencana-konten), dan klik "create branch: rencana-konten". Pastikan from nya itu from master, karena kita ingin branch nya itu dari branch master
- Ketika kita yang lagi aktif itu di branch yang baru kita buat, ketika kita commit file, pilihan pertamanya itu "commit directly to the rencana-konten branch" karena di branch itulah kita sedang membuat file baru.
- Berpindah branch itu namanya checkout.
- Cara melakukan merging:
1. Pastikan sedang berada dalam pilihan branch rencana-konten
2. Kemudian pilih compare & pull request
3. Setelah itu akan ada tampilan yang menampilkan branch apa yang ingin digabung ke branch apa, tanda "able to merge" apabila 2 branch itu mampu dimerge, bagian seperti email singkat yang berisi title dan isi untuk kita menulis pesan, dan tanda "create pull request".
4. Klik "create pull request"
5. Setelah itu di halaman repo, akan ada notifikasi di bagian "pull-requests", klik bagian itu dan buka file yang ada di situ, dan klik "merge pull request" dan "confirm merge".
- Setelah melakukan merge, branch rencana-konten masih ada, dan cara untuk menghapusnya adalah klik "branches" dan hapus branch yang ingin dihapus. 
- Kita harus melakukan create pull request, karena kita meminta pemilik branch master untuk menarik apa yang ada di dalam branch lain ke dalam branch master itu.
- Ketika kita membuat lebih dari 1 branch, ketika menggabungkan dengan master, kita harus merging nya satu per satu
- Kalau kita membuat 2 branch yang isi dari kedua branch itu ada yang mirip satu sama lain, ketika branch 1 sudah dimerge ke branch master, dan branch master yang baru ingin dimerge ke branch 2, akan ada konflik (can't automatically merge) meskipun tetap bisa "create a pull request". Sebagai pemilik master, kita yang harus "resolve conflicts" tersebut. Ketika kita mengklik "resolve conflicts", kita akan diarahkan ke code editor di mana kita harus memilih ingin menggunakan yang mana. Setelah itu, klik "mark as resolved", dan klik "commit merge", dan klik "confirm merge"