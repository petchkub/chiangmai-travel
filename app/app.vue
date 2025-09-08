<!-- file: app.vue -->
<template>
  <div>
    <!-- Navbar -->
    <nav class="bg-gray-900 text-white p-4">
      <div class="container mx-auto text-xl font-bold">
        Chiang Mai Travel Guide
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="bg-black text-white h-[400px] flex items-center justify-center">
      <h1 class="text-4xl font-bold">ยินดีต้อนรับสู่เชียงใหม่</h1>
    </section>

    <!-- Content Section -->
    <section class="container mx-auto py-12 px-4">
      <h2 class="text-2xl font-bold mb-6 text-center">สถานที่ท่องเที่ยวแนะนำ</h2>

      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-white rounded shadow p-4">
          <div class="h-40 bg-gray-300 mb-4"></div>
          <h3 class="text-xl font-semibold">ดอยสุเทพ</h3>
          <p class="text-gray-600 text-sm mt-2">
            วัดพระธาตุดอยสุเทพเป็นสัญลักษณ์สำคัญของเชียงใหม่ ตั้งอยู่บนภูเขาสูงพร้อมวิวสวยงาม
          </p>
        </div>

        <div class="bg-white rounded shadow p-4">
          <div class="h-40 bg-gray-300 mb-4"></div>
          <h3 class="text-xl font-semibold">ถนนนิมมาน</h3>
          <p class="text-gray-600 text-sm mt-2">
            ถนนสายไลฟ์สไตล์ เต็มไปด้วยคาเฟ่ ร้านอาหาร และร้านค้าแฟชั่นที่ทันสมัย
          </p>
        </div>

        <div class="bg-white rounded shadow p-4">
          <div class="h-40 bg-gray-300 mb-4"></div>
          <h3 class="text-xl font-semibold">ประตูท่าแพ</h3>
          <p class="text-gray-600 text-sm mt-2">
            แลนด์มาร์คกลางเมืองเก่า เชื่อมต่อกับกิจกรรมทางวัฒนธรรมและงานเทศกาลต่าง ๆ
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style>
/* Tailwind CSS จะช่วยให้ทำ UI ได้ง่ายขึ้น */
</style>
