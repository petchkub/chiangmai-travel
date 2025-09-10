<!-- file: app.vue -->
<template>
  <div class="min-h-screen flex flex-col">
    <!-- Navbar -->
    <nav class="bg-gray-900 text-white p-4 fixed w-full top-0 z-50 shadow-lg">
      <div class="container mx-auto text-xl font-bold">
        Chiang Mai Travel Guide
      </div>
    </nav>

    <!-- Hero Section -->
    <section
      class="relative h-[450px] flex items-center justify-center bg-center bg-cover"
      style="background-image: url('/images/welcome.png')"
    >
      <!-- Overlay -->
      <div class="absolute inset-0 bg-black/50"></div>
      <h1
        class="relative text-4xl md:text-5xl font-extrabold text-white text-center drop-shadow-lg px-6"
      >
        ยินดีต้อนรับสู่เชียงใหม่
      </h1>
    </section>

    <!-- Content Section -->
    <section class="container mx-auto py-16 px-4 flex-1">
      <h2 class="text-3xl font-bold mb-10 text-center text-gray-800">
        🌿 สถานที่ท่องเที่ยวแนะนำ
      </h2>

      <div class="grid sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Card -->
        <div
          class="bg-white rounded-xl shadow-md overflow-hidden transform hover:scale-105 hover:shadow-xl transition duration-300"
        >
          <div
            class="h-52 bg-center bg-cover"
            style="background-image: url('/images/Doisuthap.jpg')"
          ></div>
          <div class="p-5">
            <h3 class="text-xl font-semibold text-gray-900">
              วัดพระธาตุดอยสุเทพ
            </h3>
            <p class="text-gray-600 text-sm mt-3 leading-relaxed">
              วัดพระธาตุดอยสุเทพนั้นเป็นปูชนียสถานคู่เมืองเชียงใหม่มาตั้งแต่โบราณ ตั้งอยู่บนยอดดอยสุเทพ นอกจากนี้ยังมีบันไดนาคเจ็ดเศียรทอดยาวขึ้นไป 300 ขั้น และเจดีย์สีทองทรงเชียงแสนเป็นศิลปะล้านนาที่งดงาม
            </p>
          </div>
        </div>

        <!-- Card -->
        <div
          class="bg-white rounded-xl shadow-md overflow-hidden transform hover:scale-105 hover:shadow-xl transition duration-300"
        >
          <div
            class="h-52 bg-center bg-cover"
            style="background-image: url('/images/bd.jpg')"
          ></div>
          <div class="p-5">
            <h3 class="text-xl font-semibold text-gray-900">วัดอุโมงค์</h3>
            <p class="text-gray-600 text-sm mt-3 leading-relaxed">
              วัดอุโมงค์เป็นวัดเก่าแก่คู่เมืองเชียงใหม่มากว่า 700 ปี มีเอกลักษณ์คืออุโมงค์สร้างในสมัยพญากือนาเพื่อถวายพระมหาเถรจันทร์ใช้ปฏิบัติวิปัสสนากรรมฐาน ปัจจุบันนักท่องเที่ยวมักมาเดินชมความสวยงามและสงบภายในวัด
            </p>
          </div>
        </div>

        <!-- Card -->
        <div
          class="bg-white rounded-xl shadow-md overflow-hidden transform hover:scale-105 hover:shadow-xl transition duration-300"
        >
          <div
            class="h-52 bg-center bg-cover"
            style="background-image: url('/images/thapa.jpg')"
          ></div>
          <div class="p-5">
            <h3 class="text-xl font-semibold text-gray-900">ประตูท่าแพ</h3>
            <p class="text-gray-600 text-sm mt-3 leading-relaxed">
              ประตูท่าแพเป็นประตูเมืองด้านทิศตะวันออกของเมืองเชียงใหม่ชั้นใน บริเวณนี้จะเห็นแนวกำแพงเมืองเก่าสร้างด้วยอิฐ มีลานกว้างใช้จัดงานเทศกาลต่างๆ และยังเป็นแลนด์มาร์คที่นักท่องเที่ยวต้องแวะถ่ายรูป
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-300 py-6 text-center text-sm">
      © 2025 Chiang Mai Travel Guide
    </footer>
  </div>
</template>
