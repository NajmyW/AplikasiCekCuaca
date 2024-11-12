# Aplikasi Pengecekan Cuaca Sederhana

## Deskripsi
Aplikasi Java ini terintegrasi dengan API cuaca eksternal (seperti OpenWeatherMap) untuk mengambil data cuaca secara real-time. Aplikasi menampilkan kondisi cuaca secara grafis berdasarkan cuaca saat ini (cerah, berawan, hujan, dll).

## Fitur
- **Data Cuaca Real-Time**: Mengambil dan menampilkan data cuaca dari API eksternal.
- **Tampilan Cuaca Grafis**: Representasi visual dari kondisi cuaca saat ini.
- **Daftar Favorit**: Pengguna dapat menyimpan lokasi yang sering dicek ke favorit untuk akses cepat.
- **Penyimpanan Data**: Kemampuan untuk menyimpan data cuaca dalam format CSV dan memuatnya kembali ketika diperlukan.
- **Integrasi JTable**: Menampilkan data cuaca yang disimpan dalam format tabel.

## Komponen GUI
- JFrame
- JPanel
- JLabel
- JTextField
- JButton
- JComboBox

## Logika
- API eksternal untuk pengambilan data cuaca.
- GUI untuk tampilan grafis cuaca.

## Event
- `ActionListener` untuk tombol "Cek Cuaca".
- `ItemListener` untuk pemilihan lokasi dari JComboBox.

## Variasi
- Simpan dan ambil lokasi favorit dengan cepat dari JComboBox.
- Tombol untuk menyimpan dan memuat data cuaca ke dan dari file CSV.
- Fitur untuk menampilkan data cuaca yang disimpan pada JTable.

## Dependensi
- Java Development Kit (JDK) versi 8 atau lebih tinggi.
- Pustaka eksternal untuk penanganan permintaan API dan JSON.

---