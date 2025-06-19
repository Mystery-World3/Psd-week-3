# Latihan Interaktivitas di Jupyter Notebook (PSD Week 3)

Repositori ini berisi file Jupyter Notebook (`.ipynb`) untuk latihan pada pertemuan minggu ke-3 mata kuliah PSD (Praktikum Struktur Data). Latihan ini berfokus pada pembuatan antarmuka pengguna (UI) yang interaktif langsung di dalam lingkungan notebook.

---

## Deskripsi Proyek

Tujuan dari latihan ini adalah untuk memahami dan mempraktikkan cara menangani input dari pengguna secara dinamis menggunakan pustaka `ipywidgets` di Python. Notebook ini mendemonstrasikan cara membuat widget dasar seperti kolom input teks dan tombol, serta cara menghubungkannya dengan sebuah fungsi untuk memproses data saat terjadi sebuah aksi (seperti klik tombol).

Ini adalah latihan dasar yang penting untuk memahami bagaimana notebook tidak hanya digunakan untuk analisis data dan visualisasi statis, tetapi juga untuk membuat prototipe aplikasi interaktif sederhana.

---

## Teknologi dan Pustaka yang Digunakan

-   **Python:** Bahasa pemrograman utama.
-   **Jupyter Notebook:** Lingkungan kerja interaktif.
-   **ipywidgets:** Pustaka utama yang digunakan untuk membuat widget HTML interaktif di frontend notebook.

---

## Isi Notebook (`Week 3 - Latihan.ipynb`)

Notebook ini berisi kode yang mencakup:
-   **Impor Pustaka:** Mengimpor `ipywidgets` dan modul lain yang diperlukan dari `IPython.display`.
-   **Pembuatan Widget:** Kode untuk membuat instance dari widget seperti `widgets.Text` untuk kolom input dan `widgets.Button` untuk tombol.
-   **Event Handling:** Mendefinisikan sebuah fungsi yang akan dieksekusi ketika tombol ditekan (`on_click`).
-   **Tampilan Output:** Menampilkan widget yang telah dibuat dan mencetak output dari hasil interaksi pengguna.

---

## Cara Menjalankan

Untuk menjalankan dan berinteraksi dengan notebook ini, ikuti langkah-langkah berikut:

1.  **Clone Repositori:**
    ```bash
    git clone [https://github.com/Mystery-World3/Psd-week-3.git](https://github.com/Mystery-World3/Psd-week-3.git)
    ```

2.  **Siapkan Lingkungan Python:**
    Pastikan Anda memiliki Python dan Jupyter Notebook (atau JupyterLab) yang sudah terinstal.

3.  **Install Pustaka `ipywidgets`:**
    Buka terminal atau command prompt Anda dan jalankan perintah berikut untuk menginstal pustaka yang diperlukan:
    ```bash
    pip install ipywidgets
    ```

4.  **Jalankan Notebook:**
    Buka aplikasi Jupyter, navigasikan ke direktori tempat Anda menyimpan repositori, dan buka file `Week 3 - Latihan.ipynb`. Jalankan setiap sel kode secara berurutan untuk melihat hasilnya.
