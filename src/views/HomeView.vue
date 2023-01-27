<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi</p><br>
      <p>Berdasarkan kondisi saat ini dan tantangan yang akan dihadapi dalam 6 tahun mendatang serta dengan mempertimbangkan modal dasar yang dimiliki, maka Visi pembangunan Desa Muarajaya Tahun 2021-2027 adalah:,</p>
      <br>
      <p>
        “ DESA MUARAJAYA YANG MANDIRI DAN SEJAHTERA ”
      </p><br>

      <p class="text-3xl font-semibold">Misi</p><br>
      <p>Selain penyusunan Visi juga telah ditetapkan misi-misi yang memuat sesuatu pernyataan yang harus dilaksanakan oleh desa, agar tercapainya visi desa tersebut. Visi berada diatas Misi. Pernyataan Visi kemudian dijabarkan ke dalam Misi agar dapat dioperasionalkan/dikerjakan. Sebagaimana penyusunan Visi, Misi pun dalam penyusunannya menggunakan pendekatan partisipatif dan pertimbangan potensi dan kebutuhan Desa Muarajaya sebagaimana proses yang dilakukan, maka Misi Desa Muarajaya yaitu sebagai berikut:</p>
      <br>
      
    <ul>
      <li>1. Terciptanya pelayanan masyarakata yang responsif</li>
      <li>2. Pembangunan Infrastruktur yang tepat guna dan tepat sasaran</li>
      <li>3. Peningkatan sumber daya manusia yang handal dan trampil </li>
    </ul>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/SOTK.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
