OTOMATIC CROPPER

Kegunaan:
- Memilih satu folder berisi gambar.
- Menentukan area crop dengan menarik kotak menggunakan mouse.
- Menerapkan area crop yang sama secara proporsional ke seluruh gambar dalam folder.
- Menyimpan hasil ke folder output tanpa mengubah gambar asli.

Persiapan:
1. Instal Python 3.10 atau lebih baru.
2. Buka Command Prompt / Terminal.
3. Jalankan: py -m pip install pillow
   Jika perintah 'py' tidak tersedia, coba: python -m pip install pillow

Menjalankan:
1. Simpan file otomatic_cropper.py di komputer.
2. Buka Command Prompt di folder tempat file disimpan.
3. Jalankan: py otomatic_cropper.py
   Atau: python otomatic_cropper.py

Cara menggunakan:
1. Klik 'Pilih Folder Gambar'.
2. Pilih folder yang berisi gambar.
3. Pada pratinjau, klik dan tarik mouse untuk membuat kotak/ukuran yang di inginkan.
4. Gunakan tombol Sebelumnya/Berikutnya untuk memeriksa gambar lain.
5. Jika area sudah sesuai, klik 'Crop Semua Gambar'.
6. Hasil tersimpan di subfolder 'cropped' secara default, atau di folder output yang dipilih.

Catatan:
- Area crop yang dipilih akan diterapkan secara proporsional pada semua gambar.
- Hasil paling konsisten jika gambar memiliki komposisi bentuk yang sama.
- Jika gambar memiliki sudut berbeda, proses per kelompok gambar agar area crop tidak memotong objek penting.
- File asli tidak diubah. Hasil disimpan sebagai JPG dengan akhiran _crop.
