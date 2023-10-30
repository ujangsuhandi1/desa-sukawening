<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa Contoh TUgas Akhir</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Mewujudkan Kehidupan Masyarakat Desa Sukawening yang Tangguh
(Tanggap, Giat dan Utuh ) “

      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Melakukan reformasi sistem kinerja aparatur Pemerintah Desa 
             guna meningkatkan kualitas pelayanan kepada masyarakat; 
        </li>
        <li>
          2. Menyelenggarakan pemerintahan yang bersih, terbebas dari korupsi 
             serta bentuk-bentuk penyelewengan lainnya;
        </li>
        <li>
          3. Meningkatkan perekonomian masyarakat melalui pendampingan 
             berupa penyuluhan khusus kepada UKM, wiraswasta dan para petani;
        </li>
        <li>
          4. Meningkatkan mutu kesejahteraan masyarakat untuk mencapai taraf kehidupan yang lebih baik dan layak sehingga menjadi Desa yang maju dan mandiri; dan
        </li>
        <li>
          5. Membangkitkan kembali sarana olah  raga sepak bola, 
             bulu tangkis, bola volly dan lainnya;
        </li>
        <li>
          6.	Menumbuhkembangkan perekonomian masyarakat melalui pemberdayaanUsaha Mikro Kecil dan Menengah (UMKM), dan mengembangkan Ketahanan pangan menjadi sentra ekonomi masyarakat;
        </li>
        <li>
          7.	Penggalian potensi untuk program Desa Wisata, guna peningkatan 
              Perekonomian masyarakat Desa;
        </li>
        <li>
          8.	Meningktakan pelayanan kesehatan masyarakat melalui pengembangan
              dan penambahan sarana dan prasarana kesehatan
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
