# Project 2 - Proyek Analisis Data Risiko Gagal Bayar Peminjam Divisi Kredit Bank
Menyiapkan laporan untuk bank bagian kredit. mencari tahu pengaruh status perkawinan seorang nasabah dan jumlah anak yang dimilikinya terhadap probabilitas gagal bayar dalam melunasi pinjaman

Tugas Anda adalah menyiapkan laporan untuk divisi kredit suatu bank. Anda akan mencari tahu pengaruh status perkawinan seorang nasabah dan jumlah anak yang dimilikinya terhadap probabilitas gagal bayar dalam pelunasan pinjaman. Pihak bank sudah memiliki beberapa data mengenai kelayakan kredit nasabah.

Laporan Anda akan dipertimbangkan pada saat membuat penilaian kredit untuk calon nasabah. Penilaian kredit digunakan untuk mengevaluasi kemampuan calon peminjam untuk melunasi pinjaman mereka.
Dashboard Link 
- https://public.tableau.com/views/AnalisisGagalBayar/KorelasiJumlahAnak?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link
- https://public.tableau.com/views/AnalisisGagalBayar/korelasistatuskeluarga?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link
- https://public.tableau.com/views/AnalisisGagalBayar/Korelasipendapatan?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link
- https://public.tableau.com/views/AnalisisGagalBayar/tujuankreditmemengaruhipersentasegagalbayar?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

# Problem Statement :
Tujuan:
Menguji empat hipotesis:

Apakah terdapat korelasi antara memiliki anak dengan probabilitas melakukan gagal bayar pinjaman?

Apakah terdapat korelasi antara status keluarga dengan probabilitas melakukan gagal bayar pinjaman?

Apakah terdapat korelasi antara tingkat pendapatan dengan probabilitas melakukan gagal bayar pinjaman?

Bagaimana tujuan kredit memengaruhi persentase gagal bayar?

# Insights :

- Persentase gagal bayar cenderung meningkat dengan peningkatan jumlah anak, dengan pengecualian untuk jumlah anak 5 yang tidak memiliki kasus gagal bayar.
- Jumlah anak 4 memiliki persentase gagal bayar tertinggi, diikuti oleh jumlah anak 2 dan 1. Namun, jumlah anak 3 memiliki persentase gagal bayar yang lebih rendah dibandingkan dengan jumlah anak 1 dan 2.
- Status keluarga "Civil Partnership" dan "Unmarried" memiliki persentase gagal bayar yang lebih tinggi, sementara "Widow/Widower" memiliki persentase gagal bayar yang lebih rendah.
- Status keluarga "Divorced" dan "Married" berada di antara kedua Family Status tersebut, dengan persentase gagal bayar yang relatif stabil.
- Terdapat tren yang menunjukkan bahwa semakin tinggi tingkat pendapatan, persentase gagal bayar cenderung lebih rendah. Ini dapat dilihat dari tingkat persentase gagal bayar yang lebih rendah pada tingkat pendapatan seperti "Very High Income" dan "Extremely High Income".
- Sebaliknya, tingkat pendapatan yang lebih rendah seperti "Moderate Income" dan "Low Income" memiliki persentase gagal bayar yang lebih tinggi, mencapai lebih dari 8%.
- Kredit untuk membeli mobil memiliki persentase gagal bayar yang relatif tinggi, mencapai sekitar 9.36%. Hal ini mungkin disebabkan oleh nilai kredit yang lebih tinggi dan resiko gagal bayar yang lebih besar terkait dengan kepemilikan mobil.
- Kredit untuk pendidikan juga memiliki persentase gagal bayar yang cukup tinggi, sekitar 9.22%. Hal ini bisa terkait dengan kompleksitas pengelolaan utang pendidikan dan keterbatasan pendapatan pada periode studi.
- Sementara itu, kredit untuk kepemilikan properti memiliki persentase gagal bayar yang lebih rendah, sekitar 7.23%. Ini mungkin karena kepemilikan properti cenderung dianggap sebagai investasi jangka panjang dengan resiko yang lebih terukur.
