# Cara Menjalankan Program

1. Buka file ini dengan Visual Studio Code atau code editor lainnya.
2. Buka terminal yang ada di Visual Studio Code.
3. Install Virtual Environment:
   - Untuk pengguna Windows, ketik perintah berikut pada terminal:
     ```sh
     py -3 -m venv venv
     ```
   - Untuk pengguna macOS, ketik perintah berikut:
     ```sh
     python3 -m venv venv
     ```
4. Aktifkan Virtual Environment:
   - Untuk pengguna Windows:
     ```sh
     venv\Scripts\activate
     ```
   - Untuk pengguna macOS:
     ```sh
     source venv/bin/activate
     ```
   - Jika berhasil, prompt terminal akan berubah dari `base` menjadi `venv`.
5. Install Flask:
   ```sh
   pip install flask
   ```
6. Install Torch dan dependensinya:
   ```sh
   pip install torch torchvision nltk
   ```
7. Install NLTK:
   ```sh
   pip install nltk
   ```
8. Jika cara di atas tidak berhasil untuk NLTK, coba alternatif berikut:
   - Ketik `python` pada terminal.
   - Masukkan perintah berikut satu per satu:
     ```python
     import nltk
     nltk.download('punkt')
     ```
   - Setelah selesai, ketik `quit()` lalu tekan Enter.
9. Atur variabel lingkungan Flask:
   - Untuk pengguna Windows:
     ```sh
     set FLASK_APP=app.py
     ```
   - Untuk pengguna macOS:
     ```sh
     export FLASK_APP=app.py
     ```

**Selesai!** Semoga bermanfaat. 😊

