# Target BB Ideal + AI Program Generator

## Isi
- `index.html`: kalkulator IMT, hasil rentang target, dan generator program.
- `server.js`: backend Node.js yang memanggil OpenAI Responses API dengan aman.

## Menjalankan
1. Pasang Node.js 18 atau lebih baru.
2. Buka terminal di folder ini.
3. Set API key di environment terminal, bukan di file HTML:
   - macOS/Linux: `export OPENAI_API_KEY="API_KEY_ANDA"`
   - Windows PowerShell: `$env:OPENAI_API_KEY="API_KEY_ANDA"`
4. Jalankan `node server.js`.
5. Buka `http://localhost:3000`.

Model default `gpt-4.1-mini`, bisa diubah melalui `OPENAI_MODEL`.
Permintaan AI memerlukan API key dan biaya penggunaan API dapat berlaku. Jangan unggah API key ke GitHub atau membagikannya.

Jika backend/API belum tersedia, tombol generator di halaman tetap menampilkan program offline berbasis aturan; halaman tidak mengklaim bahwa mode offline adalah AI generatif.

## Acuan kesehatan
- WHO physical activity: https://www.who.int/initiatives/behealthy/physical-activity/
- CDC BMI: https://www.cdc.gov/bmi/
- CDC BMI anak/remaja: https://www.cdc.gov/bmi/child-teen-calculator/

Program bersifat edukatif, bukan diagnosis atau nasihat medis. BMI adalah alat skrining; untuk anak/remaja diperlukan penilaian sesuai usia dan jenis kelamin. Jangan gunakan untuk diet ekstrem atau mengabaikan kondisi medis.
