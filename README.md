# demo-rpa

Login ke sistem (username dan password boleh bebas), tidak ada proses authentikasi.

## Core Banking

3 Fitur Utama Core Banking:

- **Automatic CIF Creation**
  - Proses dari Find CIF, jika ada maka selesai, jika tidak maka lanjut ke Create CIF
  - Create CIF membuat CIF dengan memasukan field yang diperlukan
  - (Perform maker checker function automatically) -> nanti
  - Membuat laporan (email)
- **Bond Coupon Distribution**
  - Mendapatkan data dari email / excel tentang obligasi
  - Ambil data dan attachment dari email
  - Masuk ke Core Banking dan menginput data yang diperlukan
  - Berikan email ke checker / approver untuk meng-approve transaksi
  - Berikan report (email / pdf)
- **Live Verification Process**
  - Ambil data yang sudah diinput oleh user dari frontend.
  - Masuk ke sistem backend
  - Bandingkan kedua data pada template file
  - Tandai data yang berbeda atau aneh
  - Ambil screenshot sebagai bukti
  - Berikan report (email / pdf)
