<template>
  <div
    class="min-h-screen bg-gradient-to-br from-neutral-900 via-neutral-950 to-neutral-800 text-neutral-100 font-sans"
  >
    <header class="py-10 px-4 border-b border-neutral-800 flex flex-col items-center">
      <img
        src="/src/assets/WhatsApp Image 2025-06-07 at 09.34.12_913475db.jpg"
        alt="Avatar"
        class="w-28 h-28 rounded-full border-4 border-neutral-800 shadow-lg mb-4"
      />
      <h1 class="text-4xl font-extrabold tracking-wide mb-1">Aufa Ziya Khairi</h1>
      <p class="text-neutral-400 text-lg">Frontend Developer • UI/UX Enthusiast</p>
      <div class="flex gap-4 mt-4">
        <a
          href="mailto:aufa.ziya118@gmail.com"
          class="hover:text-white transition-colors"
          title="Email"
        >
          <i class="fa-solid fa-envelope"></i>
        </a>
        <a
          href="https://github.com/Aufaziyakhairi"
          target="_blank"
          class="hover:text-white transition-colors"
          title="GitHub"
        >
          <i class="fa-brands fa-github"></i>
        </a>
        <a
          href="https://linkedin.com/in/aufa-ziya-khairi-703303309"
          target="_blank"
          class="hover:text-white transition-colors"
          title="LinkedIn"
        >
          <i class="fa-brands fa-linkedin"></i>
        </a>
      </div>
    </header>
    <main class="max-w-5xl mx-auto px-4 py-12">
      <section class="mb-12">
        <h2 class="text-2xl font-semibold mb-4 border-l-4 border-neutral-700 pl-3">Tentang Saya</h2>
        <p class="text-neutral-300 leading-relaxed text-lg">
          Saya adalah seorang developer yang fokus pada pengembangan web modern dengan pengalaman di
          <span class="text-white font-semibold">Vue</span>,
          <span class="text-white font-semibold">Tailwind CSS</span>, dan teknologi frontend
          lainnya. Saya suka membuat UI yang bersih, minimalis, dan mudah digunakan.
          Saat ini saya pelajar SMKN 1 Ciomas, Bogor, Jawa Barat, Indonesia.
        </p>
      </section>
      <section class="mb-12">
        <h2 class="text-2xl font-semibold mb-4 border-l-4 border-neutral-700 pl-3">Projek</h2>
        <ul class="grid md:grid-cols-2 gap-8">
          <li
            class="bg-neutral-800 rounded-xl p-6 shadow-lg hover:scale-105 hover:shadow-2xl transition-all border border-neutral-700"
          >
            <h3 class="text-xl font-bold mb-2">Difia.id</h3>
            <p class="text-neutral-400 mb-3">
              Aplikasi e-commerace yang memudahkan pengguna untuk membeli dan menjual produk konveksi tas dan souvenir.
            </p>
            <a href="https://difia.kuadrattech.my.id/" class="text-neutral-200 underline hover:text-white transition" target="_blank"
              >Lihat Projek</a
            >
          </li>
        </ul>
      </section>
      <!-- Sertifikat Section -->
      <section class="mb-12">
        <h2 class="text-2xl font-semibold mb-4 border-l-4 border-neutral-700 pl-3">Sertifikat</h2>
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
          <div
            class="bg-neutral-800 rounded-xl p-6 shadow-lg border border-neutral-700 flex flex-col items-start hover:scale-105 hover:shadow-2xl transition-all"
          >
            <div class="flex items-center gap-3 mb-2">
              <i class="fa-solid fa-certificate text-yellow-400 text-2xl"></i>
              <span class="text-lg font-bold"
                >Pengenalan ke Logika Pemrograman (Programming Logic 101)
              </span>
            </div>
            <p class="text-neutral-400 mb-2">Dicoding • 2023</p>
            <embed
              src="/public/sertifikat/sertifikat_course_302_3224908_010923205058.pdf"
              type="application/pdf"
              width="100%"
              height="350px"
              class="rounded border border-neutral-700 shadow lg:h-[500px]"
            />
            <p class="text-xs text-neutral-500 mt-2">
              Jika PDF tidak tampil,
              <a
                href="/public/sertifikat/sertifikat_course_302_3224908_010923205058.pdf"
                target="_blank"
                class="underline"
                >klik di sini untuk membuka di tab baru</a
              >.
            </p>
          </div>
          <div
            class="bg-neutral-800 rounded-xl p-6 shadow-lg border border-neutral-700 flex flex-col items-start hover:scale-105 hover:shadow-2xl transition-all"
          >
            <div class="flex items-center gap-3 mb-2">
              <i class="fa-solid fa-certificate text-yellow-400 text-2xl"></i>
              <span class="text-lg font-bold">Belajar Dasar-Dasar DevOps </span>
            </div>
            <p class="text-neutral-400 mb-2">Dicoding • 2023</p>
            <embed
              src="/public/sertifikat/sertifikat_course_382_3224908_151023201345.pdf"
              type="application/pdf"
              width="100%"
              height="350px"
              class="rounded border border-neutral-700 shadow lg:h-[500px]"
            />
            <p class="text-xs text-neutral-500 mt-2">
              Jika PDF tidak tampil,
              <a
                href="/public/sertifikat/sertifikat_course_382_3224908_151023201345.pdf"
                target="_blank"
                class="underline"
                >klik di sini untuk membuka di tab baru</a
              >.
            </p>
          </div>
          <div
            class="bg-neutral-800 rounded-xl p-6 shadow-lg border border-neutral-700 flex flex-col items-start hover:scale-105 hover:shadow-2xl transition-all"
          >
            <div class="flex items-center gap-3 mb-2">
              <i class="fa-solid fa-certificate text-yellow-400 text-2xl"></i>
              <span class="text-lg font-bold">Global Game Jam 2024 x Create In Bogor </span>
            </div>
            <p class="text-neutral-400 mb-2">Dicoding • 2023</p>
            <embed
              src="/sertifikat/CIB_GGJ24_01(47).pdf"
              type="application/pdf"
              width="100%"
              height="350px"
              class="rounded border border-neutral-700 shadow lg:h-[500px]"
            />
            <p class="text-xs text-neutral-500 mt-2">
              Jika PDF tidak tampil,
              <a href="/sertifikat/CIB_GGJ24_01(47).pdf" target="_blank" class="underline"
                >klik di sini untuk membuka di tab baru</a
              >.
            </p>
          </div>
          <div
            class="bg-neutral-800 rounded-xl p-6 shadow-lg border border-neutral-700 flex flex-col items-start hover:scale-105 hover:shadow-2xl transition-all"
          >
            <div class="flex items-center gap-3 mb-2">
              <i class="fa-solid fa-certificate text-yellow-400 text-2xl"></i>
              <span class="text-lg font-bold"
                >Memulai Dasar Pemrograman untuk Menjadi Pengembang Software
              </span>
            </div>
            <p class="text-neutral-400 mb-2">Dicoding • 2023</p>
            <embed
              src="/public/sertifikat/sertifikat_course_237_3224908_010923202355.pdf"
              type="application/pdf"
              width="100%"
              height="350px"
              class="rounded border border-neutral-700 shadow lg:h-[500px]"
            />
            <p class="text-xs text-neutral-500 mt-2">
              Jika PDF tidak tampil,
              <a
                href="/public/sertifikat/sertifikat_course_237_3224908_010923202355.pdf"
                target="_blank"
                class="underline"
                >klik di sini untuk membuka di tab baru</a
              >.
            </p>
          </div>
        </div>
      </section>
      <section>
        <h2 class="text-2xl font-semibold mb-4 border-l-4 border-neutral-700 pl-3">Kontak</h2>
        <div class="flex justify-center">
          <form
            class="bg-neutral-800 rounded-xl p-6 shadow-lg border border-neutral-700 flex flex-col gap-4 w-full max-w-md"
            @submit="sendEmail"
          >
            <input
              type="text"
              placeholder="Nama"
              v-model="form.nama"
              required
              class="bg-neutral-900 border border-neutral-700 rounded px-4 py-2 text-neutral-100 focus:outline-none focus:border-white transition"
            />
            <input
              type="email"
              placeholder="Email"
              v-model="form.email"
              required
              class="bg-neutral-900 border border-neutral-700 rounded px-4 py-2 text-neutral-100 focus:outline-none focus:border-white transition"
            />
            <textarea
              placeholder="Pesan"
              rows="3"
              v-model="form.pesan"
              required
              class="bg-neutral-900 border border-neutral-700 rounded px-4 py-2 text-neutral-100 focus:outline-none focus:border-white transition"
            ></textarea>
            <button
              type="submit"
              :disabled="loading"
              class="bg-neutral-700 hover:bg-neutral-600 text-white font-semibold rounded px-4 py-2 transition disabled:opacity-60"
            >
              {{ loading ? 'Mengirim...' : 'Kirim' }}
            </button>
            <p v-if="success" class="text-green-400 mt-2">{{ success }}</p>
            <p v-if="error" class="text-red-400 mt-2">{{ error }}</p>
          </form>
        </div>
      </section>
    </main>
    <footer class="text-center py-6 text-neutral-500 border-t border-neutral-800 text-sm">
      &copy; 2025 Aufa Ziya Khairi. All rights reserved.
    </footer>
  </div>
</template>

<script>
import emailjs from 'emailjs-com'

export default {
  data() {
    return {
      form: {
        nama: '',
        email: '',
        pesan: '',
      },
      loading: false,
      success: null,
      error: null,
    }
  },
  methods: {
    async sendEmail(e) {
      e.preventDefault()
      this.loading = true
      this.success = null
      this.error = null
      try {
        await emailjs.send(
          'service_huo41o8', // ganti dengan service ID Anda
          'template_jc83iy4', // ganti dengan template ID Anda
          {
            from_name: this.form.nama,
            from_email: this.form.email,
            message: this.form.pesan,
          },
          'RJS2vCsEDYS6pSz5r', // ganti dengan public key Anda
        )
        this.success = 'Pesan berhasil dikirim!'
        this.form.nama = ''
        this.form.email = ''
        this.form.pesan = ''
      } catch (err) {
        this.error = 'Gagal mengirim pesan. Silakan coba lagi.'
      }
      this.loading = false
    },
  },
}
</script>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css');
</style>
