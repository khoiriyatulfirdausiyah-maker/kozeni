KOZENI — ASSET PILIHAN A FIX

Perubahan:
1. Asset Breakdown hanya menampilkan aset manual/non-akun.
   - Tabungan/Account Balance tidak lagi tampil di donut.
   - Jumlah Aset dan jumlah komponen donut sekarang konsisten.

2. Asset masuk ke Transaksi.
   - Tambah aset -> otomatis membuat record Transaksi tipe Aset.
   - Edit aset -> record transaksi aset ikut diperbarui.
   - Hapus aset -> record transaksi aset ikut dihapus.
   - Aset lama yang sudah tersimpan otomatis dibuatkan record transaksi saat aplikasi dibuka.
   - Filter Transaksi > Aset sekarang menampilkan aset.

3. Net Worth tetap benar:
   Net Worth = Account Balance + Asset Balance.
   Tabungan tidak double count.

Build ini tetap membawa:
- Ringkasan final
- Insight duplikat sudah dihapus
- Expense Distribution sudah dihapus
- Native Backup JSON fix
- GitHub Actions APK builder
