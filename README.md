# PinjamXYZ
Application Design Test

Design Endpoint API (Payload menggunakan JSON):

POST /api/register: Mendaftarkan pengguna baru dengan data seperti email, password, no hp, dan ktp image (upload). 
POST /api/verify-otp: Verifikasi pengguna menggunakan kode OTP yang dikirimkan ke email/HP. 
POST /api/login: Masuk ke aplikasi dengan email atau menggunakan fingerprint. 
PUT /api/user/profile: Mengubah profil pengguna seperti email, no hp, dan password, serta melakukan verifikasi dengan OTP. 


POST /api/loans/apply: Mengajukan permohonan pinjaman dengan data seperti amount. (Payload menggunakan JSON)
GET /api/loans/status: Mendapatkan status pinjaman yang diterima, ditolak, atau sedang diproses untuk pengguna.
GET /api/loans/balance: Mendapatkan saldo pinjaman yang sudah diterima.

POST /api/send-loan-approval-notification : Mengirimakn notifikasi email jika pinjaman sudah disetujui


