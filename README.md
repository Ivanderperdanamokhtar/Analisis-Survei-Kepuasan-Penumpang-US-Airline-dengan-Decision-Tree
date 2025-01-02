# Analisis Survei Kepuasan Penumpang US Airline dengan Decision Tree

## Deskripsi Proyek

Proyek ini menggunakan metode **Decision Tree** untuk menganalisis survei kepuasan penumpang maskapai penerbangan AS. Tujuannya adalah untuk memprediksi tingkat kepuasan penumpang berdasarkan berbagai fitur seperti layanan wifi inflight, online boarding, tipe perjalanan, dan kelas penerbangan. Hasil analisis dapat memberikan wawasan kepada maskapai penerbangan untuk meningkatkan layanan dan pengalaman pelanggan.

## Detail Proyek

- **Judul:** Analisis Survei Kepuasan Penumpang US Airline dengan Decision Tree
- **Penulis:**
  - Ivander Perdana Mokhtar (121450067)
  - Rangga Adi Putra (121450106)
  - Putri Intan Kirani (121450055)
  - Afifah Syaharani (121450097)
  - Audrey Ribka Desmonda M. (121450103)
- **Akurasi Model:** 89.56%
- **Dataset:** [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

## Fitur Dataset

1. **Variabel Penting:**
   - Online Boarding
   - Inflight Wifi Service
   - Type of Travel
   - Customer Type
   - Inflight Entertainment
   
2. **Variabel Tidak Signifikan:**
   - Gender
   - Age
   - Flight Distance
   - Gate Location
   - Seat Comfort
   - Check-in Service

3. **Output:**
   - Satisfaction: Satisfied, Neutral, Dissatisfied

## Metode

1. **Decision Tree:**
   - Membagi dataset berdasarkan fitur penting.
   - Menggunakan "Online Boarding" sebagai root node utama.

2. **Evaluasi Model:**
   - Residual Mean Deviance: 0.4619
   - Misclassification Error Rate: 9.8%

3. **Confusion Matrix:**
   - Neutral/Dissatisfied: Prediksi benar 16,664
   - Satisfied: Prediksi benar 11,513

## Hasil dan Kesimpulan

- **Faktor utama kepuasan:**
  - Online boarding > 4.5
  - Inflight wifi service > 3.5
  - Kelas penerbangan bukan "Eco" atau "Eco Plus"
  - Inflight entertainment > 3.5

- **Faktor utama ketidakpuasan:**
  - Online boarding ≤ 3.5
  - Inflight wifi service ≤ 4.5
  - Kelas penerbangan "Eco" atau "Eco Plus"
  - Disloyal customer

- **Rekomendasi:**
  Maskapai penerbangan perlu meningkatkan layanan wifi, hiburan inflight, dan kenyamanan boarding untuk meningkatkan kepuasan pelanggan.

