# Yazid Biografi 🌟

Selamat datang di proyek **Yazid Biografi**!  
Website ini saya buat sebagai media untuk menyimpan dan mempublikasikan perjalanan saya selama berkarya di dunia teknologi dan kreatif.

## ✨ Teknologi yang Digunakan

- **HTML** – Sebagai struktur dasar halaman.
- **Vue.js** – Framework JavaScript progresif untuk membangun antarmuka pengguna.
- **Tailwind CSS** – Utility-first CSS framework yang memberikan tampilan modern dan responsif dengan cepat.
- **Vite** – Build tool modern yang cepat dan ringan untuk proyek frontend berbasis Vue.

## ⚠️ Penggunaan

Website ini dapat dijadikan referensi atau portofolio pribadi, namun:

- **JANGAN** memperjualbelikan script atau hasil karya dari website ini.
- Gunakan dengan bijak untuk pembelajaran dan inspirasi.
- Pelanggaran terhadap ketentuan ini dapat saya tindak sesuai hukum yang berlaku.

## 🚫 Nonaktifkan Auto Refresh (HMR)

Jika Anda merasa auto-refresh mengganggu selama pengembangan, Anda dapat mematikan fitur Hot Module Reloading (HMR) dengan mengubah konfigurasi pada `vite.config.js` seperti berikut:

```js
export default defineConfig({
  plugins: [],
  server: {
    host: '0.0.0.0',
    hmr: false, // Menonaktifkan auto-refresh
  }
})
