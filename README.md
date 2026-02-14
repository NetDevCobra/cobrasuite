
<img width="673" height="298" alt="cobrasuite" src="https://github.com/user-attachments/assets/0c71fca2-7051-4e17-aa87-dcafdb5255de" />

# COBRASUITE v1.1.0
**Cybernetic Offensive & Breaching Routine Automation Suite**

Terima kasih telah menggunakan **COBRASUITE**. Ini adalah versi produksi (Release) yang telah di-bundle secara *Self-Contained*. Anda tidak perlu menginstal .NET Runtime untuk menjalankan aplikasi ini.

---

## 🛠️ Persiapan Sistem
Sebelum menjalankan, pastikan sistem Anda memiliki alat pendukung berikut (Aplikasi akan mengecek secara otomatis):
* `aircrack-ng`
* `hcxtools`
* `hashcat`

## 🚀 Cara Menjalankan
1. **Ekstrak File** (Jika di-zip):
   ```bash
   tar -xvf CobraSuite.tar.gz
   
2. Berikan Izin Eksekusi:

chmod +x CobraSuite

3. Eksekusi dengan Hak Akses Root:

sudo ./CobraSuite

📂 Struktur Folder Output

Setelah dijalankan, aplikasi akan secara otomatis mengelola folder berikut:

    /scans          : File log dan capture mentah (.cap).

    /wordlists      : Letakkan file rockyou.txt atau kamus lainnya di sini. (Masukan WordList Yang Sudah Ada Atau Yang Terbaru Di Folder Ini, Akan Ada Selection WordList)

    /hashcat_exports: File .hc22000 siap crack untuk GPU.

    reports.log     : Database kunci (password) yang berhasil didapatkan.
    
⚠️ Troubleshooting

Interface Tidak Muncul? Pastikan adapter WiFi mendukung Monitor Mode. Gunakan perintah rfkill unblock all jika WiFi terblokir secara software/hardware.

Hashcat Gagal?
Pastikan driver GPU (NVIDIA/AMD) sudah terinstal dengan benar jika ingin menggunakan akselerasi hardware.

Error Library (.so)?
Update sistem Anda dengan sudo apt update && sudo apt install -y build-essential.

🛡️ Disclaimer

Penggunaan COBRASUITE harus mematuhi hukum yang berlaku. Alat ini dirancang untuk audit keamanan profesional. Penyalahgunaan terhadap infrastruktur publik atau tanpa izin adalah tindakan ilegal.
   
   
