---
# try also 'default' to start simple
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Intro Machine Learning
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
# transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
layout: intro
---

# Intro Machine Learning 

Pengenalan Machine Learning dan Object Detection

<div class="absolute bottom-10">
  <span class="font-700">
    Miftahul Huda
  </span>
  <br />
  <span class="text-gray-500">
    Software Developer
  </span>
</div>

---
transition: slide-left
---

<div class="flex gap-5 my-10">
  <div class="w-3/4">
    <div class="text-4xl mb-5">
      Miftahul Huda
    </div>
    <div class="text-sm">
      <ul>
        <li>Fullstack Developer 5+ years exp</li>
        <li>ex-Mobile Developer @ Citilink Indonesia</li>
        <li>Teknik Informatika @ 2019</li>
      </ul>
      Awards:
      <ul>
        <li>Apple Developer Academy Graduate 2022</li>
        <li>Winner Swift Student Challenge 2022, Apple Inc</li>
        <li>Lead Google Developer Student Club (GDSC) Trunojoyo 2021</li>
        <li>3rd Hackathon FIND-IT UGM 2021</li>
        <li>Best Graduate Faculty of Engineering UTM</li>
        <li>many more...</li>
      </ul>
    </div>
    <span class="font-700">
      <a href="https://www.linkedin.com/in/iniakunhuda/">@iniakunhuda</a> |
      <a href="https://iniakunhuda.com/">iniakunhuda.com</a>
    </span>
  </div>
  <div class="w-1/4">
    <img src="/images/profil.jpg" class="w-full float-end" />
  </div>
</div>

---
transition: slide-left
layout: 3-images
imageLeft: '/images/huda/summit1.png'
imageTopRight: '/images/huda/sbydev.png'
imageBottomRight: '/images/huda/summit2.png'
---


---
transition: slide-left
class: text-center
---

# Hasil Akhir

Bikin model neural network dari dasar - implementasi

<br>

<div class="flex gap-5">
<img src="/images/hasilakhir.png" class="w-1/2 object-scale-down" style="height:320px" />
<img src="/images/hasilakhir2.png" class="w-1/2 object-scale-down" style="height:320px" />
</div>

<img src="/images/pentol/celupin.png" v-click alt="ml" class="w-1/2 object-scale-down" style="height:200px;position:absolute;right:-100px;bottom:30px" />


---
transition: slide-left
class: text-center
---

<style>
iframe {
    align-items: center;
    margin: auto;
}
</style>

## AI, AI, AI..

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/-P-ein58laA?si=s13O8LkwEUejwGxi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

@ Google I/O 2023


<!-- https://www.mentimeter.com/app/presentation/n/alv81opnohd298fiq3r62h7eze3s9ic6/edit?question=d4srd4i91dzg -->

---
layout: statement
transition: slide-left
---

# "Artificial intelligence is the new electricity"

Andrew NG, computer scientist and Coursera co-founder

---
transition: fade
---

# Penelitian AI saat ini

<br>

<img src="https://miro.medium.com/v2/resize:fit:1400/1*tAp3R2m1HExEM1uXREnEiw.png" class="h-80 object-scale-down" />

<img src="/images/pentol/brain.jpg" alt="ml" class="w-1/2 object-scale-down" style="height:200px;position:absolute;right:-100px;bottom:30px" />


---
transition: fade
---


# Sebelum masuk ke ML,

<div class="text-xl mb-5">
Kita perlu tahu dulu <span class="text-purple-500" v-mark.circle.purple>Why</span>-nya
</div>

<img src="/images/pentol/monmaaf.jpg" alt="ml" v-click.hide class="w-full object-scale-down" style="height:300px;position:absolute" />


<div v-after>
<small>Pemrograman biasa melibatkan penulisan aturan yang diekspresikan dalam bahasa pemrograman (if, else, for-loop, dsb), yang berfungsi pada data dan memberikan kita jawaban.</small>

<img src="/images/figure1.png" alt="game" class="w-7/12 mt-5" />

<p class="text-sm">
Contoh: Game Breakout
</p>
</div>

<!-- Di sini, pergerakan bola dapat ditentukan oleh properti dx dan dy. Ketika bola mengenai sebuah balok, balok tersebut dihapus, dan kecepatan bola meningkat serta berubah arah. Kode bekerja berdasarkan data tentang situasi permainan. -->

---
transition: fade
---

Contoh lainnya: 

<p>
Fungsi menghitung P/E (Rasio Harga terhadap Pendapatan)
</p>
<br>

<!-- <img src="/images/figure2.png" alt="finance data" class="w-full mt-10" /> -->

```ts {all|1-2|3-4|5}

// rules
calcPE(stock) {
  let price = readPrice(); // data
  let earnings = readEarnings(); // data
  return (price/earnings);
}
```

<!-- Misalnya kamu bikin aplikasi keuangan dan fungsi untuk menghitung P/E-->

---
transition: fade
---


<div class="grid grid-cols-1 gap-5">
  <div>
    <p class="text-sm">
      Tradisional Programming
    </p>
    <p class="text-3xl">
      Rules + Data = Answers
    </p>
  </div>
  <div>
    <img src="/images/figure3.png" alt="tradisional" class="w-full mt-5" />
  </div>
</div>

---

<div class="grid grid-cols-2 gap-5">
  <div>
    <p class="text-sm">
      Tradisional Programming
    </p>
    <p class="text-3xl">
      Rules + Data = Answers
    </p>
  </div>
  <div>
    <img src="/images/figure3.png" alt="tradisional" class="w-full mt-5" />
  </div>
</div>


<div class="grid grid-cols-4 gap-5 mt-10">
  <div v-click>
    <img src="/images/figure41.png" class="w-full h-60 mb-3" />
    Jalan Kaki
  </div>
  <div v-click>
    <img src="/images/figure42.png" class="w-full h-60 mb-3" />
    + Lari
  </div>
  <div v-click>
    <img src="/images/figure43.png" class="w-full h-60 mb-3" />
    + Sepeda
  </div>
  <div v-click>
    <img src="/images/figure44.png" class="w-full h-60 mb-3" />
    ?? Golf
  </div>
</div>


<!-- What about other scenarios? Usually, they are infeasible to develop because the code is too complex. It’s just not possible to write code to handle them.
Consider, for example, activity detection. Fitness monitors that can detect our activity are a recent innovation, not just because of the availability of cheap and small hard‐ ware, but also because the algorithms to handle detection weren’t previously feasible. Let’s explore why. -->

---
layout: statement
---

<img src="/images/pentol/janganya.png" alt="ml" class="w-full object-scale-down" style="height:300px;" />

## Jangan bikin manual rulesnya satu satu


---
layout: fact
transition: fade
---

<span class="text-8xl"  v-mark.underline.purple>
Machine Learning
</span>

<!--
Bisa mengatasi hal tersebut..
-->

---
transition: fade
---

<br>

<div class="grid grid-cols-2 gap-5">
  <div>
    <p class="text-sm">
      Tradisional Programming
    </p>
    <p class="text-3xl">
      Rules + Data = Answers
    </p>
  </div>
  <div class="h-36 bg-white">
    <img src="/images/figure3.png" alt="tradisional" class="w-full mt-5" />
  </div>
</div>


<div class="grid grid-cols-2 gap-5 mt-20">
  <div>
    <p class="text-sm">
      Machine Learning
    </p>
    <p class="text-3xl">
      Answer + Data = Rules
    </p>
  </div>
  <div class="h-36 bg-white">
    <img src="/images/figure5.png" alt="ml" class="w-full mt-5" />
  </div>
</div>


---


<div class="grid grid-cols-2 gap-5">
  <div>
    <p class="text-sm">
      Machine Learning
    </p>
    <p class="text-3xl">
      Answer + Data = Rules
    </p>
  </div>
  <div>
    <img src="/images/figure5.png" alt="ml" class="w-full mt-5" />
  </div>
</div>


<div v-click>
<img src="/images/figure6.png" alt="ml" class="w-8/12 mt-10"/>

<p class="text-xl">
Sekarang, tugas kita sebagai programmer berubah dari menentukan rule, menjadi menulis kode yang mencocokkan data dengan label
</p>
</div>


<!-- So what are the implications of this? Well, now instead of us trying to figure out what the rules are, we get lots of data about our scenario, we label that data, and the com‐ puter can figure out what the rules are that make one piece of data match a particular label and another piece of data match a different label.
How would this work for our activity detection scenario? Well, we can look at all the sensors that give us data about this person. If they have a wearable that detects infor‐ mation such as heart rate, location, speed, etc.—and if we collect a lot of instances of this data while they’re doing different activities—we end up with a scenario of having data that says “This is what walking looks like,” “This is what running looks like,” and so on 

Now our job as programmers changes from figuring out the rules, to determining the activities, to writing the code that matches the data to the labels. If we can do this, then we can expand the scenarios that we can implement with code. Machine learn‐ ing is a technique that enables us to do this, but in order to get started, we’ll need a framework—and that’s where TensorFlow enters the picture.
-->


---

# Jenis Machine Learning
<br>

<ul>
  <li>
    Supervised Learning
  </li>
  <li>
    Unsupervised Learning
  </li>
  <li>
    Reinforcement Learning
  </li>
</ul>

---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li class="text-purple-500 font-bold">
        Supervised Learning
      </li>
      <li>
        Unsupervised Learning
      </li>
      <li>
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    <img src="/images/figure7.png" alt="ml" class="w-full" />
    <p>
      Contoh yang umum adalah klasifikasi. Filter spam pada Gmail: filter ini dilatih dengan training data banyak email beserta kelasnya (spam atau bukan spam), dan harus belajar bagaimana mengklasifikasikan email baru.
    </p>
  </div>
</div>


---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li class="text-purple-500 font-bold">
        Supervised Learning
      </li>
      <li>
        Unsupervised Learning
      </li>
      <li>
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    <img src="/images/figure71.png" alt="ml" class="w-full h-60 object-scale-down" />
    <p>
      Contoh lainnya adalah regresi, yang melibatkan prediksi nilai numerik. Misalnya, memprediksi harga saham berdasarkan fitur-fiturnya.
    </p>
  </div>
</div>


---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li class="text-purple-500 font-bold">
        Supervised Learning
      </li>
      <li>
        Unsupervised Learning
      </li>
      <li>
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    <p>
      Ada yang bisa kasih contoh lagi kasus supervised learning? 🙌🏻
    </p>
  </div>
</div>


---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li class="text-purple-500 font-bold">
        Supervised Learning
      </li>
      <li>
        Unsupervised Learning
      </li>
      <li>
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    Beberapa metode yang termasuk 
    <br><br>
    <ul>
      <li>k-Nearest Neighbors</li>
      <li>Linear Regression</li>
      <li>Logistic Regression</li>
      <li>Support Vector Machines (SVMs)</li>
      <li>Decision Trees and Random Forests</li>
      <li>Neural networks</li>
    </ul>
  </div>
</div>


---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li>
        Supervised Learning
      </li>
      <li class="text-purple-500 font-bold">
        Unsupervised Learning
      </li>
      <li>
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    <img src="/images/figure73.png" alt="ml" class="w-full h-64 object-scale-down" />
    <p class="text-sm">
      Unsupervised learning memiliki training data yang belum berlabel. Salah satu contohnya adalah klastering (Clustering). Dimana dataset yang kita punya belum memiliki label, dan kita ingin mengelompokkan data ke dalam beberapa kelompok. Pengelompokan ini dilakukan berdasarkan kemiripan fitur-fitur data.
    </p>
  </div>
</div>


---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li>
        Supervised Learning
      </li>
      <li class="text-purple-500 font-bold">
        Unsupervised Learning
      </li>
      <li>
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    <img src="/images/figure72.png" alt="ml" class="w-full h-72 object-scale-down" />
    <p class="text-sm">
      Di kasus ini misalnya, kita punya data pengunjung mall dan ingin mengelompokkan data ke dalam beberapa kelompok. Tujuannya untuk memberikan rekomendasi diskon & produk yang sesuai dengan kelompok tersebut.
    </p>
  </div>
</div>


---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li>
        Supervised Learning
      </li>
      <li class="text-purple-500 font-bold">
        Unsupervised Learning
      </li>
      <li>
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    Beberapa metode yang termasuk 
    <br><br>
    <ul>
      <li>
        Clustering
        <ul>
          <li>K-Means</li>
          <li>Hierarchical Cluster Analysis (HCA)</li>
          <li>Anomaly detection and novelty detection One-class SVM</li>
        </ul>
      </li>
      <li>
        Visualization and dimensionality reduction
        <ul>
          <li>Principal Component Analysis (PCA)</li>
          <li>Kernel PCA</li>
        </ul>
      </li>
    </ul>
  </div>
</div>


---

# Jenis Machine Learning

<br>

<div class="flex gap-10">
  <div class="w-2/5">
    <ul>
      <li>
        Supervised Learning
      </li>
      <li>
        Unsupervised Learning
      </li>
      <li class="text-purple-500 font-bold">
        Reinforcement Learning
      </li>
    </ul>
  </div>
  <div class="w-3/5">
    <img src="/images/figure74.png" alt="ml" class="w-full h-62 object-scale-down" />
    <p class="text-sm">
      Reinforcement Learning memiliki disebut agen dalam konteks ini, dapat mengamati lingkungan, memilih dan melakukan tindakan, serta mendapatkan imbalan (atau hukuman dalam bentuk imbalan negatif). Agen tersebut harus belajar sendiri apa strategi terbaik, yang disebut policy, untuk mendapatkan imbalan paling banyak dari waktu ke waktu. Policy mendefinisikan tindakan apa yang harus dipilih oleh agen ketika berada dalam situasi tertentu.
    </p>
  </div>
</div>

---
transition: fade
---

<img src="/images/image1.png" alt="ml" class="w-full object-scale-down" style="height:450px" />

---
transition: fade
---

<img src="/images/image2.png" alt="ml" class="w-full object-scale-down" style="height:450px" />


---
transition: fade
class: text-center
---

Machine Learning Pipeline di Industri

<img src="/images/image3.png" alt="ml" class="w-full object-scale-down" style="height:300px" />

<img src="/images/pentol/gwenchana.png" v-click alt="ml" class="w-1/2 object-scale-down" style="height:200px;position:absolute;right:-100px;bottom:30px" />


https://towardsdatascience.com/machine-learning-pipelines-feature-engineering-numbers-29f53aaec82a


---
transition: fade
class: text-center
---

Proses Training dan Testing

<img src="/images/image4.png" alt="ml" class="w-full object-scale-down" style="height:300px" />

Split data menjadi training dan testing set ini penting untuk menghindari overfitting (model terlalu baik pada data training, tapi tidak baik pada data testing) dan underfitting (model terlalu sederhana untuk menangkap pola data). Berapa rasio yang baik untuk split data ini?


---
transition: fade
class: text-center
---

<img src="/images/image5.png" alt="ml" class="w-full object-scale-down mb-3" style="height:100px" />

<img src="/images/image6.png" alt="ml" class="w-full object-scale-down mb-10" style="height:250px" />

TensorFlow, Keras, PyTorch adalah tiga framework populer yang digunakan dalam pengembangan dan implementasi model machine learning, khususnya deep learning



<!--  TensorFlow dikembangkan oleh Google dan terkenal karena skalabilitasnya dalam produksi, Keras adalah API tingkat tinggi yang berjalan di atas TensorFlow atau Theano, memudahkan proses pembuatan model neural network, sedangkan PyTorch, yang dikembangkan oleh Facebook, dikenal karena fleksibilitas dan kemudahannya dalam debugging dengan dukungan penuh untuk komputasi dinamis. Ketiga framework ini mempermudah peneliti dan praktisi untuk membangun, melatih, serta menerapkan model kecerdasan buatan dengan lebih efisien dan cepat. -->


---
transition: slide-up
class: text-center
---


<img src="/images/image7.png" alt="ml" class="w-full object-scale-down" style="height:350px" />


---
transition: fade
---

<img src="https://media.makeameme.org/created/demo-time-finally.jpg" alt="ml" class="w-full object-scale-down" style="height:480px" />


---
layout: statement
---

# s.id/wargalab-ml


---
layout: statement
class: text-center
---

<img src="/images/pentol/sombong.jpg" alt="ml" class="w-full object-scale-down mb-3" style="height:170px" />


# Terima Kasih 🙏🏻

Tetap semangat belajar!

<br>
<hr />
<br>

<span class="text-purple-500">
iniakunhuda.com
</span>


---
layout: statement
---


<img src="/images/huda/image.png" alt="ml" class="w-full object-scale-down mb-3" style="height:350px" />


Mentoring gratis, akan dilakukan secara online 1-1 sekitar 15 menitan. Bisa diskusi karir, software developer, web, mobile, komunitas, manchester united, one piece dan lainnyaa 🙌🏻