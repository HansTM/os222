# `RESULT`

Folder `RESULT` ini berisi hasil akhir dari pekerjaan di VM tiap minggu, yang nantinya akan dienkripsi ke dalam bentuk `myW00.tar.bz2.asc`.

Folder ini dirilis pada akhir dari kelas Sistem Operasi, dan sebelumnya hanya disimpan secara lokal di VM. Rilis ini hanya sebuah inisiatif sendiri semata, bukan diperintahkan menurut silabus.

## Catatan

1. Pada `WEEK02`/`W02`, *username*-nya adalah `hans`, yang lalu diganti menjadi `HansTM` pada minggu-minggu selanjutnya. *Username* `hans` adalah sebuah kesalahan. Jangan ulangi ini lagi!
2. Dikarenakan adanya masalah saat menjalankan LFS di minggu ke-8, VM harus diulang dari dalam *snapshot* yang dibuat pada minggu ke-4. Ini disebutkan jika nantinya ada inkonsistensi, namun seharusnya ini tidak akan mempengaruhi hasilnya.
   ```mermaid
    %%{init: { 'logLevel': 'debug', 'theme': 'base', 'gitGraph': {'showBranches': true, 'showCommitLabel':true, 'mainBranchName': 'first-run'}} }%%
    gitGraph
    commit id: "W00"
    commit id: "W01"
    commit id: "W02"
    commit id: "W03"
    commit id: "W04"
    branch second-run
    checkout first-run
    commit id: "W05"
    commit id: "W06"
    commit id: "W07"
    commit id: "W08"
    checkout second-run
    commit id: "W09"
    commit id: "W10"
   ```