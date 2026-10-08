# Nama Tim: Rizal dan Muhaimin    
## Repository: (https://github.com/mhmnardh/LKPD_6/)

 1 Developer Muhaimin
 2 Developer Rizal 

## C. Misi 1: Memahami Merge Conflict
 1. Apa yang dimaksud dengan Merge Conflict dalam Git?
Merge conflict dalam Git adalah kondisi ketika Git tidak bisa menggabungkan (merge) perubahan dari dua branch secara otomatis karena ada bagian baris kode yang sama diubah dengan instruksi berbeda

## E. Misi 3: Memicu Conflict
Tugas: Tuliskan pesan error/peringatan yang muncul di terminal saat terjadi conflict <br>
PS D:\Tugas Rizal XI RPL 1\LKPD_6> git merge main <br>
Auto-merging index.html <br>
CONFLICT (content): Merge conflict in index.html <br>
Automatic merge failed; fix conflicts and then commit the result. <br>

## H. Checkpoint 1 (Evaluasi Praktik)
[x]Skenario branch fitur-header-a dan fitur-header-b berhasil dibuat. <br>
[x]Anggota tim berhasil melihat pesan peringatan Merge Conflict di terminal. <br>
[x]File berhasil disatukan kembali dan di-commit tanpa meninggalkan sisa karakter penanda. <br>
[x]Log graph menunjukkan cabang yang berpisah dan menyatu kembali (3-way merge). <br>

## I. Simulasi Masalah (Study Kasus)
1. Kasus 1: Saat terjadi conflict, Budi panik. Ia ingin membatalkan proses merge yang sedang bermasalah agar kembali ke posisi aman sebelum merge. Perintah Git apa yang harus ia gunakan? <br>
    = Budi harus mengetik Git merge --abort di git bash/terminal untuk membatalkan merge yang akan dilakukan <br>

2. Kasus 2: Apakah merge conflict selalu berarti ada anggota tim yang melakukan kesalahan (error)? Jelaskan alasannya berdasarkan simulasi yang baru saja kalian lakukan! <br>
    = Tidak selalu karena dari simulasi yang kita lakukan, bisa jadi dua hal tersebut merupakan perubahan yang baik hanya perubahannya di tempat yang sama dan membutuhkan observasi yang jelas <br>