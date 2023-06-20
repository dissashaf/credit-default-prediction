# Credit Card Default Prediction

Pada proyek ini akan dilakukan pembuatan model prediksi untuk mengklasifikasikan golongan *default payment* atau gagal bayar kartu kredit. Pembayaran *default* kartu kredit mengacu pada situasi di mana pemegang kartu kredit gagal melakukan pembayaran minimum yang diperlukan untuk kartu kredit pada tanggal jatuh tempo--biasanya dari tiga sampai enam bulan tunggakan. *Default* terjadi ketika penerbit kartu memutuskan untuk menutup rekening peminjam karena pembayaran yang terlewatkan (sumber: [gocardless](https://gocardless.com/guides/posts/payment-defaults/#:~:text=What%20is%20a%20payment%20default,account%20because%20of%20missed%20payments.)).

Dalam proyek ini, klasifikasi terbagi atas golongan 'no' (index = 0) yang berarti tidak terjadi *default payment*, dan 'yes' (index = 1) yang berarti penerbit kartu menerapkan *default payment* untuk pemegang kartu pada bulan setelahnya. 

**Problem statement:** 

Diperlukan model klasifikasi dengan akurasi tinggi untuk dapat memprediksi *default payment* yang disebabkan oleh tunggakan kartu kredit. Diperlukan adanya percobaan beberapa jenis model untuk dapat membandingkan serta mendapatkan model paling akurat. Akurasi tinggi diperlukan untuk dapat memprediksi pembayaran bulanan kartu kredit dengan tepat; tentunya untuk mengurangi resiko kerugian untuk pihak penerbit kartu.

**Dataset:**

[Dataset](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=ml_datasets&t=credit_card_default&page=table&project=molten-team-383513&ws=!1m9!1m4!4m3!1sbigquery-public-data!2sml_datasets!3scredit_card_default!1m3!8m2!1s681236883696!2s2e90e5b0d93b4ae8bb309369d2b00670!1m5!1m4!1m3!1smolten-team-383513!2sbquxjob_76149282_188144f8290!3sUS) yang akan dipakai adalah dataset “Credit Card Default” yang berasal klien kredit di Taiwan dari bulan April hingga September pada tahun 2005. Dataset ini memiliki 24 kolom serta 2965 baris data.
