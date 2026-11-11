# Griya Pusaka Larasati — Website Contoh Toko Katalog Produk

Website contoh katalog produk untuk pelanggan. Semua isi masih **dummy / contoh** dan mudah diganti.

- **Nama toko (dummy):** Griya Pusaka Larasati
- **Nomor WhatsApp (dummy):** 0812-3456-7890
- **Produk contoh:** 12 produk — 5 pusaka / keris, 4 minyak wangi, 3 jasa (termasuk jasa tempa keris dan perawatan pusaka)
- **Fitur:** katalog produk (nama, deskripsi, harga), cari produk, filter kategori, urutkan harga, detail produk, tombol Pesan via WhatsApp per produk, dan Mode Pemilik untuk tambah / edit / hapus produk.

## Cara deploy ke Vercel

1. Di Vercel, pilih **Add New > Project**, lalu **Import Git Repository** dan pilih repo ini.
2. Team: Taufiq Aziz's projects
3. Project Name: `griya-pusaka-larasati`
4. Root Directory: `./`
5. Framework Preset: **Other** (website statis HTML saja, tidak pakai framework dan tidak butuh build)
6. Environment Variables: tidak perlu diisi
7. Klik **Deploy**.

## Catatan penting (versi contoh)

<!-- Trigger redeploy Vercel — 11 Nov 2026 11:45 WIB -->

Ini website statis contoh. Perubahan di Mode Pemilik hanya berlaku selama halaman dibuka, belum tersimpan permanen dan belum terlihat pengunjung lain. Untuk versi produksi, produk sebaiknya disimpan di database (misalnya Supabase) agar perubahan pemilik langsung terlihat semua pengunjung.
