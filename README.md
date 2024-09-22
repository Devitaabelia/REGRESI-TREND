# REGRESI-TREND
Repository ini berisi kode dan dataset yang digunakan untuk melakukan analisis regresi tren, dengan fokus pada pengaruh hari-hari besar keagamaan seperti Idul Fitri dan Idul Adha terhadap jumlah keberangkatan penumpang. Proyek ini bertujuan untuk mengidentifikasi bagaimana tren jumlah keberangkatan dipengaruhi oleh momen-momen spesifik dalam kalender, terutama hari besar keagamaan.

# Deskripsi Dataset
Dataset ini berisi data bulanan mengenai jumlah keberangkatan penumpang, dengan variabel dependen "Jumlah Keberangkatan Penumpang". Selain itu, terdapat variabel dummy seperti DummyBulanIdulFitri, DummyIdulFitri, DummyBulanIdulAdha, dan DummyIdulAdha yang menunjukkan adanya momen Idul Fitri dan Idul Adha serta bulan terkait, yang digunakan untuk mengukur dampaknya terhadap jumlah penumpang. Data ini digunakan untuk menganalisis tren keberangkatan penumpang serta pengaruh hari-hari besar keagamaan dalam periode waktu tertentu.

# Model yang Digunakan
Analisis ini menggunakan model regresi tren untuk mengidentifikasi pola jangka panjang dalam jumlah keberangkatan penumpang, dengan tambahan variabel dummy untuk menangkap efek musiman yang disebabkan oleh Idul Fitri dan Idul Adha. Terdapat dua model utama:
- Regresi Tren dengan Dummy Idul Fitri: Menganalisis pengaruh tren dan variabel dummy Idul Fitri serta bulan Idul Fitri terhadap jumlah keberangkatan penumpang.
- Regresi Tren dengan Dummy Idul Adha: Menganalisis pengaruh tren dan variabel dummy Idul Adha serta bulan Idul Adha terhadap jumlah keberangkatan penumpang.
