# Rancangan Sistem Aplikasi Izin Cuti

1. Deskripsi Sistem:
Sistem ini adalah aplikasi berbasis web yang memudahkan karyawan untuk mengajukan izin cuti dan memungkinkan manajemen untuk mengelola permohonan izin cuti.

2. Fitur Utama:

2.1. Pengajuan Izin Cuti: Karyawan dapat mengajukan izin cuti melalui aplikasi dengan mengisi formulir permohonan yang mencakup tanggal awal, tanggal akhir, jenis izin cuti, alasan, kontak darurat, serta pengganti karyawan yang cuti.
Ketentuan : 
1.	Cuti tahunan, dapat di pakai Ketika karyawan > 1 tahun kerja (karyawan tetap), dan akan mengurangi hak cuti tahunan. Lama pengajuan cuti tidak boleh lebih besar dari sisa hak cuti
2.	Cuti Khusus, tidak mengurangi hak cuti tahunan
3.	Cuti sakit, jika terdapat surat dokter maka cuti tidak memotong hak cuti, jika tidak ada surat dokter maka akan memotong hak cuti 

2.2. Persetujuan Izin Cuti: Manajemen dapat meninjau dan menyetujui atau menolak permohonan izin cuti melalui aplikasi. Mereka juga dapat memberikan alasan jika permohonan ditolak.
Ketentuan : 
1.	Jika cuti disetujui, maka akan mengurangi jatah cuti tahunan, dan akan mengirimkan Notifikasi ke pembuat dan pengganti.
2.	Jika cuti ditolak, maka akan mengirimkan notifikasi penolakan beserta alasannya ke pada pembuat.
3.	Persetujuan dilakukan oleh atasan (Manager)

2.3. Kalender Izin Cuti: Aplikasi akan menyediakan kalender yang menampilkan semua izin cuti yang disetujui dan izin cuti yang sudah diajukan oleh karyawan, memudahkan manajemen untuk merencanakan sumber daya.

2.4. Notifikasi: Karyawan akan menerima notifikasi melalui email atau pesan dalam aplikasi mengenai status permohonan izin cuti mereka.

2.5. Laporan Izin Cuti: Manajemen dapat menghasilkan laporan tentang penggunaan izin cuti karyawan, termasuk statistik tentang jenis izin cuti yang paling sering diajukan.
