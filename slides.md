---
# try also 'default' to start simple
theme: default
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
background: https://source.unsplash.com/XgeZu2jBaVI/1920x1080
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: fade-out
# use UnoCSS
css: unocss
---

# Becoming an Open-Source Contributor

<p class="c-gray-400">
  Memahami Dunia Open-Source: Dari Ide hingga Berkontribusi.
</p>

Kalwabed Rizki

<div class="text-sm abs-bl !pb-8 pl-12">
  <div class="flex items-center">
    <img src="/kpb-logo.png" class="w-18" />

  <div class="text-left">
    <span>Komunitas Programmer Banyuwangi</span>
    <p class="c-gray-400 !p-0 !m-0">
      18 Februari 2023
    </p>
  </div>
  </div>
</div>

---
title: Kalwabed Rizki
layout: two-cols
---

<div class="mt-8">
  <h1 class="!c-white !text-5xl !pt-8">
    Kalwabed Rizki
  </h1>

  <div class="c-gray-400 mt-8">
    <p>
    Fullstack web engineer at F&B startup.
    </p>
    <p>
    TypeScript and open-source enthusiasts.
    </p>
    <p>
    Part of JogjaJS.
    </p>
  </div>

  <div class="flex gap-4 items-center mt-12 text-sm">
    <ph-github-logo class="c-gray-500" />
    <a href="https://github.com/kalwabed">kalwabed</a>
  </div>
  <div class="flex gap-4 items-center mt-4 text-sm">
    <ph-globe class="c-gray-500" />
    <a href="https://www.kalwabed.xyz">kalwabed.xyz</a>
  </div>
  <div class="flex gap-4 items-center mt-4 text-sm">
    <ph-instagram-logo class="c-gray-500" />
    <a href="https://www.instagram.com/kalwabed">kalwabed</a>
  </div>
  <div class="flex gap-4 items-center mt-4 text-sm">
    <ph-twitter-logo class="c-gray-500" />
    <a href="https://twitter.com/kalwabedrzk">kalwabedrzk</a>
</div>


</div>

::right::

<img src="/kalwabed.jpg" class="rd-full w-48 mt-10 ml-auto" />

<!--
Nama saya Kalwabed Rizki. Saya seorang Fullstack Web Engineer di salah satu F&B Startup di Indonesia. Saya sudah menggeluti dunia industri teknologi sejak sekitar 2 tahunan ini. Saya tinggal di Jogja, sekarang lagi pulang kampung di Banyuwangi. Aktif di komunitas JogjaJS, dan Menjadi member KPB sejak 2019.
-->

---
layout: section
---

# Open source?

Let me introduce myself.

---
---

# What is Open Source?
Perangkat lunak yang memiliki sumber kode terbuka yang dapat dilihat, diedit, dan dikembangkan oleh siapa saja.

<div class="flex justify-between">
<img src="/open-source.png" width="400" />
<img src="/closed-source.png" width="400" />
</div>

---
---

# Open Source History

<img src="/oss-history.png" alt="OSS history"  />
<!--
Sejarah open-source software dimulai pada tahun **1950-an dan 1960-an**, saat programmer memulai untuk bekerja sama dan berbagi kode sumber mereka. Pada tahun **1968, Richard Stallman memulai proyek GNU (GNU's Not Unix)**, bertujuan untuk menciptakan sistem operasi kompatibel Unix yang sumber kodenya terbuka.

Pada tahun 1985, Stallman menciptakan organisasi Free Software Foundation (FSF) untuk mempromosikan dan mempertahankan filosofi perangkat lunak bebas dan terbuka. **Pada tahun 1989, Stallman mengeluarkan lisensi publik general GNU (GPL)**, yang menjadi lisensi open-source paling populer hingga sekarang.

**Pada tahun 1991, Linus Torvalds memulai proyek untuk membuat sistem operasi berbasis Unix yang terbuka, yang dikenal sebagai Linux**. Pada tahun 1993, permintaan akan perangkat lunak open-source mulai meningkat, dan banyak perusahaan mulai mengadopsi dan mengembangkan teknologi ini.

Sejak saat itu, open-source software telah berkembang menjadi industri besar, dengan ribuan perangkat lunak dan proyek terbuka yang tersedia bagi siapa saja untuk digunakan dan dikembangkan. Saat ini, open-source software digunakan dalam berbagai sektor, termasuk bisnis, pemerintahan, pendidikan, dan teknologi.
-->

---
layout: statement
---

# But why...?
Kenapa harus open source?

---
class: text-2xl
---

# Why Are People Choosing Open Source?

<div class="flex justify-between">

1. Fleksibilitas <ph-check class="c-green" />
2. Kualitas <ph-check class="c-green" />
3. Harga <ph-check class="c-green" />
4. Keamanan <ph-check class="c-green" />
5. Kolaborasi <ph-check class="c-green" />
6. Transparansi <ph-check class="c-green" />

<img src="/power-rangers.jpg" alt="Power rangers" class="rd-lg" width="400" />

</div>

<!--
1. Fleksibilitas: Perangkat lunak open-source dapat dilihat, diedit, dan dikembangkan oleh siapa saja, memungkinkan pengguna untuk menyesuaikan dan memodifikasi perangkat lunak untuk memenuhi kebutuhan mereka.
2. Kualitas: Karena sumber kode terbuka, perangkat lunak open-source dapat diperiksa dan ditingkatkan oleh komunitas global, memastikan bahwa perangkat lunak bekerja dengan baik dan memenuhi standar kualitas tertentu.
3. Harga: Perangkat lunak open-source biasanya gratis, membuatnya menjadi pilihan yang lebih murah bagi individu dan organisasi yang memiliki anggaran terbatas.
4. Keamanan: Karena sumber kode terbuka, masalah keamanan dapat segera dikenali dan difix oleh komunitas, memastikan bahwa perangkat lunak aman untuk digunakan.
5. Kolaborasi: Perangkat lunak open-source memungkinkan kolaborasi antar programmer dan organisasi dari seluruh dunia, mempercepat inovasi dan pengembangan.
6. Transparansi: Perangkat lunak open-source memungkinkan pengguna untuk memahami bagaimana perangkat lunak bekerja dan memastikan bahwa perangkat lunak tidak melakukan hal-hal yang merugikan.
-->

---
layout: section
---
# Where we should getting started?
Ingin mulai, tapi dari mana?

---
layout: statement
---

# Contribution Is Not Only by Code

---
title: Contributions
layout: center
---

# Kita juga bisa berkontribusi dengan...

- Melaporkan jika ada bug
- Membuat tools untuk mempermudah penggunaan
- Membuat dokumentasi
- Dukungan secara finansial (cth. donasi, sponsor)

---
layout: section
---

# Before your first contribution
Sebelum mulai berkontribusi, apa yang harus dipersiapkan?

---
---

# Git
Version control system.

<img src="/git-branch.png" alt="Git branch" width="400" />

- Branching
- Merging
- Conflict resolution
- Rebasing
- Git Workflow

---
---

# Github <ph-github-logo-duotone />
Git hosting service.

<div class="flex justify-between">

- Repository
- Forking
- Pull Request
- Issues
- Github Actions

<div>
<img src="/gh-pr-flow.png" class="rd" alt="Github PR flow" width="450" />

[pull-request-review-process](https://blog.comtradedigital.com/blog/pull-request-review-process)
</div>
</div>

---
layout: statement
---

# Did I mention about license?

---
layout: center
title: MIT License
---
The most commonly used license for OSS...

<img src="/mit.png" width="500" alt="MIT illustration" />

<!--
Sebelum menggunakan berbagai jenis software kita juga perlu memperhatikan tentang lisensinya. Lisensi yang paling umum digunakan untuk OSS adalah MIT.
Lisensi ini dikeluarkan oleh Massachusetts Institute of Technology (MIT) dan memungkinkan pengguna untuk menggunakan, memodifikasi, dan membagikan perangkat lunak yang dilisensikan dengan lisensi ini.
Lisensi MIT sangat mudah dipahami dan menyediakan fleksibilitas tinggi bagi pengguna dan pengembang. Hal ini membuat lisensi MIT sangat populer untuk proyek perangkat lunak open-source, termasuk beberapa proyek populer seperti Ruby on Rails, Django, dan React.
Lisensi MIT sangat ringan dan hanya membutuhkan beberapa syarat minimal, seperti pemberitahuan atas hak cipta dan pengecualian tanggung jawab hukum.
-->

---
---

# Recap
- Open source software adalah jenis software yang terbuka secara kode sumber dan pengembangan
- Tidak hanya dengan menulis kode, untuk berkontribusi juga bisa melalui banyak cara
- MIT adalah lisensi yang umum digunakan untuk OSS
- Git dan Github adalah instrumen OSS yang sangat penting

---
layout: section
---

# Thank You!

Slides bisa dijumpai di [kpb-oss.netlify.app](https://kpb-oss.netlify.app)

---
layout: statement
---

# I'm not done yet... <ph-smiley />
Belum sempurna kalau belum membuat kontribusi.

---
layout: center
---

# Your first contribution

<ph-github-logo /> [kalwabed/kpb-oss](https://github.com/kalwabed/kpb-oss)

---
src: ./pages/contributors.md
hide: false
---
