# MuhammadAlghifarie-PBO2-Tugas6
Berikut adalah file README dalam Bahasa Indonesia:

### README File (Bahasa Indonesia)

```markdown
# Aplikasi CekCuaca

## Ringkasan
Aplikasi CekCuaca memungkinkan pengguna untuk memeriksa cuaca di kota tertentu. Aplikasi ini mengambil data dari API cuaca dan menampilkannya dengan ikon yang mewakili kondisi cuaca. Aplikasi ini juga memungkinkan pengguna untuk menyimpan kota favorit dan data cuaca ke file CSV.

## Fitur
- Memeriksa cuaca untuk kota tertentu dengan memasukkan nama kota atau memilihnya dari dropdown.
- Melihat suhu dan deskripsi cuaca untuk kota yang dipilih.
- Menambahkan kota ke favorit untuk akses cepat di lain waktu.
- Menyimpan data cuaca ke file CSV.
- Menampilkan ikon cuaca berdasarkan kondisi cuaca (berawan, hujan, cerah, dll).

## Persyaratan
- Java Development Kit (JDK) versi 8 atau lebih tinggi.
- Pustaka JSON seperti `org.json` untuk menangani respons API (dapat ditambahkan melalui Maven atau secara manual).
- Koneksi internet untuk mengambil data cuaca (menggunakan endpoint API).

## Persiapan
1. Clone atau unduh file proyek.
2. Buka proyek di IDE favorit Anda (misalnya IntelliJ IDEA, NetBeans).
3. Tambahkan dependensi yang diperlukan untuk menangani JSON (`org.json` library).
4. Kompilasi dan jalankan kelas `CekCuaca`.

## Cara Penggunaan
1. **Cek Cuaca**: Masukkan nama kota di kolom teks atau pilih dari combo box, kemudian klik "Cek Cuaca" untuk mengambil data cuaca.
2. **Simpan Data**: Setelah mengecek cuaca, klik "Simpan" untuk menyimpan kota, suhu, dan deskripsi cuaca ke file CSV.
3. **Tambah ke Favorit**: Masukkan nama kota dan klik "Favorit" untuk menambahkannya ke dropdown list untuk digunakan di masa depan.
4. **Muat Data**: Klik "Muat Data" untuk memuat data cuaca yang telah disimpan sebelumnya.

## Contoh Respons API Cuaca (untuk pengujian)
```json
{
    "main": {
        "temp": 25.3
    },
    "weather": [
        {
            "description": "clear sky"
        }
    ]
}
```

