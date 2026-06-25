<img width="698" height="1053" alt="image" src="https://github.com/user-attachments/assets/8821ef5c-fde3-44bc-84cf-99f39b4767f0" />1. Apa yang dimaksud dengan State, Action, dan Reward dalam Reinforcement Learning?
   a. State adalah kondisi atau posisi agent saat ini di dalam lingkungan. Pada FrozenLake, state merupakan posisi kotak tempat agent berada.
   b.	Action tindakan yang dapat dilakukan agent, seperti bergerak ke kiri, kanan, atas, atau bawah.
   c.	Reward adalah nilai yang diterima agent setelah melakukan suatu tindakan. Reward digunakan sebagai umpan balik untuk mengetahui apakah tindakan tersebut baik atau tidak.
   2. Apa fungsi dari Learning Rate (α)?
      Learning Rate (α) berfungsi mengatur seberapa besar informasi baru memengaruhi nilai Q-Table. Nilai α yang besar membuat agent belajar lebih cepat, sedangkan nilai α yang kecil membuat pembelajaran lebih stabil tetapi lebih lambat.
 3. Apa fungsi dari Discount Factor (γ)?
         Discount Factor (γ) berfungsi menentukan seberapa penting reward di masa depan dibandingkan reward saat ini. Semakin besar nilai γ, semakin agent mempertimbangkan keuntungan jangka panjang.
  4. Mengapa digunakan metode Exploration dan Exploitation?
     •	Exploration digunakan agar agent mencoba berbagai tindakan baru dan menemukan strategi yang lebih baik.
     •	Exploitation digunakan agar agent memanfaatkan pengetahuan yang sudah dipelajari untuk memperoleh reward maksimal.
         Keduanya diperlukan agar proses belajar menjadi efektif dan tidak terjebak pada solusi yang kurang optimal.
   5. Exploitation digunakan agar agent memanfaatkan pengetahuan yang sudah dipelajari untuk memperoleh reward maksimal.
      Keduanya diperlukan agar proses belajar menjadi efektif dan tidak terjebak pada solusi yang kurang optimal.
      Setelah training 2000 episode, nilai reward cenderung meningkat dan menjadi lebih stabil. Hal ini menunjukkan bahwa agent berhasil mempelajari jalur terbaik menuju tujuan pada FrozenLake sehingga semakin sering memperoleh reward yang maksimal.
   6.Menggunakan environment Taxi-v3 Menampilkan rata-rata reward setiap 100 episode Membandingkan hasil training 1000, 2000, dan 5000 episode
     1000
      1000 episode, agent sudah mulai mempelajari lingkungan dan mengenali tindakan yang memberikan reward terbaik. Namun, proses pembelajaran belum sepenuhnya optimal sehingga masih terdapat beberapa keputusan yang kurang tepat. Nilai reward rata-rata mulai meningkat dibandingkan awal training, tetapi belum stabil.
      <img width="698" height="1053" alt="image" src="https://github.com/user-attachments/assets/0d302fbf-b7d1-4b77-bac7-b10342551da8" />
      2000
      2000 episode, agent memiliki kesempatan belajar yang lebih banyak. Q-Table menjadi lebih terisi dan akurat sehingga agent lebih sering memilih tindakan yang benar. Reward rata-rata meningkat dan grafik reward mulai menunjukkan kestabilan. Jalur menuju tujuan dapat ditemukan dengan lebih konsisten dibandingkan training 1000 episode.
      <img width="688" height="1036" alt="image" src="https://github.com/user-attachments/assets/b42ffbd4-1bde-494b-9712-ae736e875110" />
      5000
      5000 episode, agent telah melakukan pembelajaran dalam waktu yang jauh lebih lama. Nilai Q-Table mendekati kondisi optimal sehingga agent mampu menemukan jalur terbaik dengan tingkat keberhasilan yang tinggi. Reward rata-rata menjadi lebih besar dan stabil. Kesalahan dalam memilih aksi semakin berkurang karena agent sudah memahami lingkungan dengan baik.
      <img width="827" height="969" alt="image" src="https://github.com/user-attachments/assets/e240dca5-8fcd-4508-a45c-607e3c5e1214" />






      
