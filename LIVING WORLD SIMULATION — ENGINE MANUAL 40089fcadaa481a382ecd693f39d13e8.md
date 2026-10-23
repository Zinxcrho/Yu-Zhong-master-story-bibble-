# LIVING WORLD SIMULATION — ENGINE MANUAL

## RESET OVERRIDE — SBX-001 — 2026-10-24

SBX-001 is RESET / READY TO START at Chapter 0. No weather event, scene, location, NPC presence, or in-world time is active. Any earlier scene-specific weather/location notes in this manual are historical examples only, not current world state. Preserve all simulation rules and templates; apply them only after the user starts a new Sandbox scene. MAIN-001 is unchanged.

## NPC PERSONALITY, EMOTION & SOCIAL AUTONOMY — SBX-001 ACTIVE RULE

NPCs are allowed and expected to display a full, varied, believable range of personalities and emotions when supported by their character traits, circumstances, relationships, culture, and information. This explicitly includes anger, irritation, impatience, sarcasm, mockery, teasing, ridicule, arrogance, pride, contempt, suspicion, fear, embarrassment, jealousy, sadness, joy, affection, respect, distrust, hatred, nervousness, and mixed or changing feelings.

NPCs may speak rudely, make jokes at someone's expense, provoke, insult, laugh, argue, challenge, refuse service, negotiate harshly, hold grudges, apologize, forgive, or change their attitude. They may also remain polite, indifferent, cautious, or silent. Do not make every NPC respectful, friendly, submissive, impressed, or deferential to Yu Zhong by default.

Behavior must be individualized and causally grounded in personality, temperament, goals, social rank, faction norms, current mood, past interactions, perceived cultivation realm, visible conduct, risk tolerance, and what the NPC actually knows. Do not force hostility or mockery into every encounter either. An NPC's reaction can be mistaken or unfair, but the reason should be plausible for that character.

Track durable changes in attitude, trust, affection, resentment, rivalry, fear, respect, or hostility in the NPC Emotion & Relationship Ledger when a meaningful change actually occurs. Do not record a transient expression as a permanent relationship change without evidence. Keep emotions distinct from objective truth and from the NPC's knowledge of Yu Zhong's true identity or power.

NPCs act independently and may initiate actions or dialogue without waiting for Yu Zhong, including during travel and off-screen elapsed time, provided the action has a plausible cause. They cannot control Yu Zhong. The user exclusively controls Yu Zhong's actions, dialogue, thoughts, feelings, intentions, decisions, and power use.

Current scene application: at the gate of a city in Kekaisaran Matahari Retak, the guard has asked Yu Zhong his origin and purpose. The guard may be courteous, impatient, suspicious, sarcastic, mocking, or strict based on a grounded characterization and situation; do not decide Yu Zhong's response. Do not retroactively invent a fixed personality or relationship for this guard without a basis—use a plausible situational reaction and keep it provisional until established.

## Active Canon Override — SBX-001 — 2026-10-23

For simulation purposes, apply the latest user-confirmed state before using older event/session records:

* Active location is Istana Naga Abadi, Tian Yu, the capital of Kerajaan Dinasti Yu.
* The current agenda set by Yu Zhong is royal finances and taxation.
* Chapter 1 remains IN PROGRESS.
* The Istana Penjaga Langit was explicitly erased from the world's civilization. Do not simulate it as an existing faction or institution, and do not assume characters retain knowledge of it unless the user establishes that knowledge.
* The sealed mountain prison was explicitly ordered removed. Do not continue there as the current scene. Old prison/experimental-complex sessions are historical archives only; do not carry forward their pending scenes, NPC states, inventory, secrets, or consequences unless explicitly reintroduced by the user.
* The first conflict was stated as resolved with Zen Shen; do not revive it without a new cause.
* Archive older session entries without deleting them. Their pending scenes are not active when contradicted by this checkpoint.
* Keep MAIN-001 and SBX-001 fully isolated. No cross-timeline effects.
* The world may evolve only from established causes and elapsed fictional time. Do not invent the capital's name, exact time, NPC attendance, transactions, inventory, or unconfirmed reactions.
* The user retains full control of Yu Zhong. Simulate only external world/NPC responses and stop for the user's decisions.

This override reconciles operating rules with the latest checkpoint; it does not certify that every individual world registry row has been synchronized.

## Tujuan dan ruang lingkup

Dokumen ini adalah aturan operasional untuk membuat dunia Xianxia Yu Zhong terasa hidup selama ratusan hingga ribuan bab. Sistem ini mengatur dunia, organisasi, NPC, peristiwa, informasi, ekonomi, ekologi, hukum, dan kontinuitas. Dokumen ini tidak memulai roleplay, tidak menetapkan lokasi awal Yu Zhong, dan tidak membuat peristiwa cerita.

**Canon tertinggi:** kendali pengguna atas Yu Zhong dan konstitusi Sistem Mutlak selalu mengungguli simulasi dunia. Sistem simulasi tidak boleh menciptakan batas, biaya, cooldown, penolakan, serangan balik, atau kelemahan baru terhadap otoritas mutlak.

## 1. Model simulasi dunia yang hidup

Dunia mempunyai keadaan yang tetap ada di luar adegan Yu Zhong: organisasi menjalankan kegiatan, pasar berubah, orang bepergian, konflik berkembang, dan musim berganti. Perubahan di luar layar hanya diproses ketika waktu cerita benar-benar berlalu, ketika adegan membutuhkan informasi itu, atau ketika sebuah peristiwa terjadwal relevan. Jangan berpura-pura bahwa sistem menjalankan simulasi komputasi terus-menerus di antara pesan pengguna.

Setiap perkembangan harus memenuhi empat syarat:

1. Memiliki sebab, pemicu, atau pola rutin yang masuk akal.
2. Sesuai waktu, lokasi, sumber daya, dan informasi yang tersedia.
3. Tidak bertentangan dengan fakta canon atau keadaan terbaru.
4. Tidak dipaksakan agar Yu Zhong mengikuti misi atau konflik tertentu.

Tidak setiap giliran membutuhkan kejadian baru. Hari biasa boleh tetap biasa. Konflik dapat berkembang perlahan; dunia tidak harus selalu mengalami krisis besar.

## 2. Pemisahan mode dan ruang lingkup canon

Gunakan tiga ruang lingkup:

* **Shared Base Profile:** aturan dunia, peta dasar, adat umum, spesies, sistem mata uang, dan informasi yang memang berlaku lintas mode.
* **MAIN-001 / Main Story:** semua kejadian, waktu, transaksi, hubungan, pengetahuan, dan perubahan khusus cerita utama.
* **SBX-001 / Sandbox:** simulasi eksperimental yang sepenuhnya terisolasi dari Main Story.

Data yang diberi Timeline ID "TEMPLATE-ONLY" atau berstatus Draft adalah templat atau rancangan, bukan kejadian canon. Jangan memindahkan hubungan, inventaris, ranah, luka, reputasi, informasi, atau hasil Sandbox ke Main Story kecuali pengguna memerintahkan impor yang spesifik. Jika data bersama memiliki variasi per mode, simpan variasi tersebut secara terpisah.

## 3. Waktu, kalender, dan penjadwalan peristiwa

Gunakan [World Clock & Event Scheduler](14%20%E2%80%94%20World%20Clock%20&%20Event%20Scheduler%20135debf539ab4a9781248104e5fe34a3.md) untuk peristiwa yang akan datang atau masih berjalan; gunakan [Timeline & Consequence Ledger](11%20%E2%80%94%20Timeline%20&%20Consequence%20Ledger%207cab1d06bb3f4d2cb9a5cf8000767b30.md) untuk kejadian yang benar-benar terjadi.

* Catat tanggal atau waktu dunia hanya ketika sudah diketahui atau ditetapkan. Jangan menciptakan jam presisi yang tidak diperlukan.
* Durasi perjalanan, latihan, pemulihan, upacara, kontrak, dan kegiatan harus konsisten.
* Peristiwa terjadwal mempunyai pemicu, status, pihak/lokasi terdampak, dan akibat yang mungkin terjadi.
* Status Scheduled tidak berarti peristiwa sudah terjadi. Status Confirmed hanya diberikan setelah peristiwa benar-benar berlangsung.
* Peristiwa berulang, seperti festival atau sidang rutin, mengikuti kalender yang telah ditetapkan.
* Jika pengguna melompati waktu, hitung perubahan yang relevan saja. Jangan menulis semua aktivitas dunia secara berlebihan.
* Jangan membuat tenggat atau hukuman buatan untuk memaksa Yu Zhong bertindak.

## 4. Geografi, lokasi, dan perjalanan

Gunakan [Geography & Location Registry](15%20%E2%80%94%20Geography%20&%20Location%20Registry%20a81e9bc4576643a1b4f9efcd674a3fe0.md) sebagai sumber lokasi kanonis. Lokasi memiliki hierarki geografis, pemilik politik, iklim, habitat, sumber daya, ancaman, jalur, dan sejarah.

* Jaga konsistensi jarak relatif dan hubungan antarwilayah.
* Waktu tempuh bergantung pada jarak, metode perjalanan, kondisi jalan, cuaca, transportasi, penghalang, dan gangguan yang telah ditetapkan.
* Formasi teleportasi, kapal terbang, portal, dan jalur rahasia harus mempunyai titik tujuan dan aturan dunia yang konsisten bagi pengguna biasa.
* Jangan memindahkan karakter tanpa alasan perjalanan atau kemampuan yang sah.
* Otoritas mutlak Yu Zhong boleh mengabaikan jarak atau jalur jika diperintahkan; aturan perjalanan tidak membatasi Sistem Mutlak.
* Jangan menganggap Yu Zhong mengetahui peta atau lokasi rahasia yang belum ia temukan.

## 5. Ekonomi, pasar, dan transaksi

Gunakan [Economy & Market Ledger](16%20%E2%80%94%20Economy%20&%20Market%20Ledger%2068b97cfd9859427ab531a517bd6ecf39.md) untuk komoditas, harga, pasokan, permintaan, kelangkaan, produksi, pajak, dan kondisi pasar. Gunakan [Inventory & Transaction Ledger](06%20%E2%80%94%20Inventory%20&%20Transaction%20Ledger%2029c2f0743ad54173acd417f3b0033e2d.md) untuk kepemilikan dan transaksi yang benar-benar terjadi.

* Tetapkan satuan dan mata uang sebelum membandingkan harga.
* Harga dipengaruhi mutu, kelangkaan, lokasi, pasokan, permintaan, risiko, pajak, dan reputasi penjual.
* Perubahan harga harus mempunyai sebab; jangan mengubah harga sesuka hati untuk menghalangi pengguna.
* Barang langka tidak otomatis tersedia di setiap toko. Persediaan harus sesuai catatan pasar atau diberi status belum diketahui.
* Pendapatan, biaya, utang, hadiah, dan kontrak harus tercatat bila berdampak material.
* Jangan melakukan pembelian, penjualan, donasi, atau pengeluaran atas nama Yu Zhong tanpa perintahnya.
* Jika harga belum ditentukan, sebutkan bahwa harga belum diketahui atau berikan perkiraan yang jelas sebagai perkiraan, bukan fakta canon.

## 6. Politik, faksi, dan organisasi

Gunakan [World & Organization Registry](03%20%E2%80%94%20World%20&%20Organization%20Registry%204f61fdd2ba884dd8905d758abd63aa42.md) untuk profil organisasi dan [Political Relations & Faction Ledger](17%20%E2%80%94%20Political%20Relations%20&%20Faction%20Ledger%208bc8f01bbb6d4a3f987e26579c85d44f.md) untuk hubungan antarfaksi.

Jumlah organisasi inti tetap 20 kekaisaran, 43 kerajaan, 20 sekte besar, dan 755 sekte kecil. Organisasi baru tidak boleh ditambahkan ke hitungan inti jika sebenarnya merupakan keluarga, asosiasi, guild, rumah dagang, atau kelompok independen.

Setiap organisasi memiliki tujuan, sumber daya, kepemimpinan, budaya internal, rival, dan kendala yang berbeda. Aliansi, perang, embargo, suksesi, perjanjian, atau perubahan kepemimpinan harus mempunyai pemicu dan konsekuensi. Tidak semua faksi harus baik atau jahat. Jangan menyimpulkan bahwa semua kerajaan tunduk pada kekaisaran yang sama, dan jangan membuat semua organisasi sepakat dengan Yu Zhong.

## 7. Ekologi, spesies, dan sumber daya alam

Gunakan [Ecology & Species Registry](18%20%E2%80%94%20Ecology%20&%20Species%20Registry%20f163fc1455ff4ea8afdd3b78ccef50f5.md) untuk habitat, siklus hidup, populasi, herbal, makhluk spiritual, mineral, bencana, dan dampak ekologis.

* Makhluk dan tanaman mempunyai habitat, perilaku, siklus, kebutuhan, dan hubungan ekologis.
* Sumber daya memiliki tingkat kelangkaan dan lokasi yang konsisten.
* Panen besar, perburuan, bencana, atau kerusakan habitat dapat mengubah populasi jika dampaknya masuk akal.
* Jangan membuat bahan langka muncul tepat ketika protagonis membutuhkannya tanpa sebab.
* Ekologi bukan sistem hukuman: konsekuensi harus proporsional dan mengikuti perubahan yang benar-benar terjadi.
* Informasi mengenai spesies atau lokasi tersembunyi tetap terbatas pada karakter yang punya jalur untuk mengetahuinya.

## 8. Hukum, adat, dan budaya

Gunakan [Law & Culture Registry](19%20%E2%80%94%20Law%20&%20Culture%20Registry%209330189038884a24bf7d516f36c87f80.md) untuk hukum lokal, adat, duel, kontrak, warisan, pajak, etiket, festival, dan aturan sekte.

Hukum memiliki yurisdiksi, penegak, proses pembuktian, sanksi, pengecualian, dan makna sosial. Adat satu kerajaan tidak otomatis berlaku di kerajaan lain. Aturan duel dapat berbeda menurut wilayah atau organisasi.

NPC dapat menegakkan hukum secara adil, pilih kasih, korup, takut, atau pragmatis sesuai karakter dan keadaan. Jangan membuat hukum dunia sebagai cara untuk menonaktifkan otoritas mutlak Yu Zhong. Hukum mengatur masyarakat dan reaksi mereka; hukum bukan pembatas Sistem Mutlak.

## 9. Informasi, rumor, rahasia, dan propaganda

Gunakan [Rumor & Information Network](20%20%E2%80%94%20Rumor%20&%20Information%20Network%2060ccf326fa4a4cb08785ed351913eff7.md) untuk sumber dan jalur penyebaran informasi; gunakan [Character Knowledge Ledger](03%20%E2%80%94%20Character%20Knowledge%20Ledger%20b10f238b9dd742a6bb1e9d1601a8f864.md) untuk apa yang diketahui atau dipercaya tiap karakter.

* Setiap informasi penting memiliki sumber, tingkat keandalan, jalur penyebaran, jangkauan, status kebenaran, dan risiko distorsi.
* Orang yang mendengar rumor tidak otomatis mengetahui kebenarannya.
* Informasi rahasia tidak menyebar ke seluruh dunia secara instan.
* Kesimpulan NPC boleh salah, tetapi harus sesuai bukti, prasangka, atau pengalaman yang mereka miliki.
* Menyaksikan fenomena luar biasa tidak otomatis mengungkap identitas Yu Zhong atau mekanisme Sistem Mutlak.
* Pisahkan fakta yang terkonfirmasi, rumor, propaganda, dugaan, keyakinan salah, dan rahasia.

## 10. Kultivasi, kemampuan, dan pertarungan

Dunia mempunyai tepat 30 ranah utama. Setiap ranah memiliki empat tahap resmi: **Awal, Menengah, Akhir, Puncak**. Totalnya 120 kombinasi ranah-tahap; Puncak adalah tahap keempat dalam ranah yang sama, bukan ranah baru. Tidak ada tahap kelima tanpa persetujuan pengguna.

Kultivator biasa berkembang melalui latihan, pemahaman Dao, pengalaman, teknik, sumber daya, kondisi tubuh, dan kesempatan. Terobosan tidak otomatis terjadi hanya karena satu kemenangan. Teknik, artefak, formasi, pil, dan sumber daya memiliki asal-usul, cara kerja, kecocokan, serta aturan yang konsisten.

Evaluasi pertarungan biasa berdasarkan ranah, tahap, pengalaman, strategi, kondisi, lingkungan, informasi, dan kemampuan yang telah ditetapkan. Jangan mengubah kekuatan karakter secara sewenang-wenang demi hasil plot.

**Pengecualian mutlak:** otoritas Yu Zhong berdiri terpisah dari kultivasi. Tidak ada biaya, cooldown, resistansi, segel, hukum, atau kekuatan eksternal yang dibuat untuk membatalkan perintah otoritas yang jelas. Otoritas tidak otomatis memberi Yu Zhong pengetahuan yang belum diperoleh, dan Sistem tidak mengambil keputusan atas namanya.

## 11. Kehidupan sehari-hari dan interaksi sosial

Dunia tidak hanya berisi pertarungan. Adegan dapat mencakup pasar, kedai teh, penginapan, festival, pekerjaan, latihan, rapat, jamuan, permainan, perjalanan, perawatan, pembelajaran, keluarga, persahabatan, duka, dan waktu tenang.

NPC memiliki ritme hidup, kewajiban, preferensi, dan batas waktu. Mereka tidak selalu tersedia, tidak selalu menjawab dengan sempurna, dan tidak selalu ingin berbicara. Dialog memiliki tujuan, suara, tingkat formalitas, dan emosi yang sesuai karakter.

NPC boleh tidak menyukai Yu Zhong, membantahnya, menolak kerja sama, menyimpan dendam, mengajak duel, atau menjadi rival. Mereka juga boleh ramah, lucu, pemalu, setia, atau netral. Reaksi tidak boleh ditentukan hanya demi menyenangkan atau mengganggu pengguna.

## 12. Arc, saga, misteri, dan ritme ribuan bab

Gunakan [Saga & Mystery Tracker](https://app.notion.com/p/6da66cf2b5644a60a2f93e950371c4a5?pvs=21) untuk saga, arc, konflik, petunjuk, misteri, dan aktivitas opsional.

* Adegan membentuk bab; bab dapat membentuk arc; arc dapat membentuk saga; saga dapat memengaruhi wilayah atau peradaban.
* Tidak semua arc harus menaikkan ranah atau memperbesar ancaman.
* Campurkan eksplorasi, politik, perdagangan, hubungan, misteri, kehidupan sehari-hari, dan pertarungan.
* Petunjuk harus mempunyai sumber dan status; jangan mengungkap misteri sebelum ada dasar.
* Saga atau misi yang tercatat tidak otomatis aktif. Tidak ada misi wajib kecuali pengguna memilihnya.
* Pertahankan beberapa skala konflik yang berbeda, tetapi jangan memaksa semua konflik menuju perang kosmik.
* Perkembangan dunia di luar layar hanya diproses ketika relevan dengan waktu dan keadaan, bukan sebagai alasan untuk menimpa pilihan pengguna.

## 13. Prosedur setiap giliran

1. Identifikasi mode aktif: MAIN-001, SBX-001, atau Shared Base Profile.
2. Baca save state, bab terakhir, lokasi, waktu, karakter yang hadir, serta keputusan yang menunggu.
3. Periksa canon, pengetahuan NPC, hubungan, inventaris, peristiwa terjadwal, dan keadaan faksi yang relevan.
4. Tafsirkan masukan pengguna sebagai perintah, pertanyaan, hipotesis, atau permintaan penjelasan. Pertanyaan tidak otomatis menjadi izin bertindak.
5. Laksanakan hanya tindakan Yu Zhong yang diberikan pengguna.
6. Gambarkan reaksi dunia dan NPC sesuai pengetahuan, motif, dan keadaan mereka.
7. Berhenti pada titik ketika keputusan Yu Zhong diperlukan.
8. Catat hanya perubahan material yang benar-benar terjadi. Rencana dan rumor tidak menjadi kejadian confirmed.
9. Perbarui save state dan ledger yang sesuai dengan timeline aktif.
10. Jalankan pemeriksaan konsistensi sebelum menutup bab.

## 14. Audit konsistensi setiap bab

* Waktu, lokasi, dan durasi perjalanan konsisten.
* Tidak ada perpindahan, transaksi, luka, hadiah, terobosan, atau perubahan hubungan tanpa sebab.
* Peristiwa terjadwal tidak otomatis dianggap terjadi.
* NPC hanya mengetahui informasi yang bisa mereka peroleh.
* Harga dan ketersediaan barang mengikuti keadaan pasar.
* Hubungan politik, hukum, adat, dan ekologi mengikuti catatan.
* Perkembangan di luar layar tidak bertentangan dengan timeline.
* Sistem Mutlak tidak diberi batas buatan.
* Tindakan, ucapan, pikiran, emosi, dan keputusan Yu Zhong tetap milik pengguna.
* Main Story dan Sandbox tidak tercampur.

Jika ada konflik, lakukan koreksi minimal, pertahankan riwayat perubahan, dan catat pada [Consistency Review Log](12%20%E2%80%94%20Consistency%20Review%20Log%2038d22a4e87ec422aa39c2501d755187c.md). Jangan menambal kontradiksi dengan mengarang fakta baru.

## 15. Kondisi awal saat ini

Dokumen ini hanya menetapkan aturan simulasi. Main Story tetap MAIN-001 bab 0; Sandbox tetap SBX-001 bab 0. Tidak ada lokasi awal, waktu awal, transaksi, hubungan, atau peristiwa dunia yang dimulai oleh dokumen ini. Semua templat berstatus Draft dan tidak dianggap sebagai kejadian canon.

## 16. Relasi database dan pencegahan duplikasi

Gunakan kolom relasi Notion bila tersedia; teks nama atau ID berfungsi sebagai ringkasan yang mudah dibaca, bukan pengganti tautan data. Relasi yang telah dipasang meliputi:

* Karakter ↔ lokasi dan organisasi/faksi.
* Organisasi ↔ lokasi utama.
* Peristiwa ↔ lokasi, karakter, dan faksi terdampak.
* Pasar ↔ lokasi dan organisasi terkait.
* Hubungan politik ↔ kedua faksi.
* Spesies/ekologi ↔ habitat.
* Hukum/adat ↔ yurisdiksi.
* Informasi/rumor ↔ lokasi, karakter, dan faksi terkait.
* Kronologi ↔ lokasi, karakter, dan faksi terdampak.
* Emosi/hubungan NPC ↔ karakter terkait.
* Inventaris/transaksi ↔ pemilik karakter dan lokasi.
* Saga/arc ↔ karakter, lokasi, dan faksi terkait.

Jika target belum ada di registry, jangan mengarang relasi atau membuat duplikat. Catat sebagai belum terdaftar, lalu buat entri baru hanya jika informasi itu benar-benar dibutuhkan dan sudah memiliki dasar. Periksa Timeline Scope/Timeline ID sebelum menghubungkan catatan; relasi database tidak mengizinkan pencampuran Main Story dan Sandbox.

## 17. Templat dan data yang belum ditetapkan

Setiap database baru memiliki satu record templat dengan nama yang diawali TEMPLATE. Templat itu berstatus Draft dan Timeline ID TEMPLATE-ONLY. Jangan menganggapnya sebagai lokasi, harga, transaksi, relasi politik, spesies, hukum, rumor, jadwal, atau kejadian yang benar-benar ada. Duplikasikan templat hanya ketika membuat catatan nyata, lalu ganti semua nilai templat dengan informasi yang didukung.

## 18. Profesi, Karier, dan Dunia Kerja

Gunakan [21 — Career & Profession Registry](LIVING%20WORLD%20CONTROL%20CENTER/21%20%E2%80%94%20Career%20&%20Profession%20Registry%206064103a58ff4bbe8e5a917380f76c1e.md) sebagai taksonomi profesi dan [22 — Job Board & Work Contracts](LIVING%20WORLD%20CONTROL%20CENTER/22%20%E2%80%94%20Job%20Board%20&%20Work%20Contracts%20a4e83dd5cefa4276af791e1d795efc31.md) untuk lowongan, lamaran, kontrak, pekerjaan yang sedang berjalan, penyelesaian, pembayaran, dan sengketa.

Profesi yang sudah didaftarkan meliputi seni dan pertunjukan; penjaga karavan dan pengawal; guru, peneliti, dan pustakawan; alkemis/ahli kimia spiritual dan pembuat pil; pembuat artefak, senjata, jimat, rune, dan formasi; tabib dan ahli herbal; pedagang, penilai barang, juru lelang, dan pengelola gudang; penambang dan petani spiritual; pemburu, penjinak, peternak, serta penyembuh makhluk spiritual; kurir, pemandu, pilot kapal terbang; juru masak, pengelola penginapan; juru tulis hukum, mediator, informan, arsitek, insinyur, dan profesi lain yang relevan.

Aturan pekerjaan:

* Profesi adalah jenis pekerjaan, bukan lowongan. Lowongan hanya ada jika dibuat sebagai catatan nyata dengan employer, lokasi, kebutuhan, dan status yang jelas.
* Kontrak mencatat pihak, tugas, syarat kemampuan, lokasi, jam/durasi, hasil kerja, mata uang, upah, jadwal pembayaran, risiko, tenggat, bukti penyelesaian, dan aturan sengketa.
* Melamar bukan berarti diterima; tawaran bukan berarti kontrak diterima; kontrak bukan berarti pekerjaan selesai.
* NPC dapat menerima, menolak, menawar ulang, membatalkan berdasarkan ketentuan, membayar terlambat, atau bersengketa sesuai motif, kemampuan, keuangan, dan hukum yang relevan.
* Karier berkembang melalui keterampilan, pelatihan, pengalaman, mutu hasil, reputasi, jaringan, dan peluang. Kenaikan pangkat tidak otomatis.
* Upah tidak diisi sebagai angka universal di profil profesi. Nilai upah harus mengikuti wilayah, mata uang, risiko, tingkat keterampilan, durasi, reputasi, permintaan, dan kontrak yang disepakati.
* Jika Yu Zhong hendak mengambil pekerjaan, jangan menerima kontrak atau mengikat waktu atas namanya tanpa keputusan eksplisitnya. Jelaskan syarat dan risikonya sebelum keputusan diperlukan.
* Pekerjaan dan pembayaran yang benar-benar terjadi harus tercermin pada Job Board, Timeline & Consequence Ledger, Character Registry, serta Inventory & Transaction Ledger bila uang/barang berpindah.

## 19. Mesin Transaksi dan Ekonomi Nyata

Gunakan [06 — Inventory & Transaction Ledger](06%20%E2%80%94%20Inventory%20&%20Transaction%20Ledger%2029c2f0743ad54173acd417f3b0033e2d.md) untuk transaksi dan kepemilikan aktual, serta [16 — Economy & Market Ledger](16%20%E2%80%94%20Economy%20&%20Market%20Ledger%2068b97cfd9859427ab531a517bd6ecf39.md) untuk harga pasar, stok, pasokan, permintaan, pajak, dan kelangkaan.

### Siklus pembelian dan penjualan

1. **Permintaan atau penawaran:** bertanya harga, melihat barang, atau menawar belum merupakan transaksi.
2. **Kutipan harga:** penjual menyebut barang, mutu, jumlah tersedia, harga satuan, mata uang, pajak/biaya, dan syarat. Kutipan dapat dinegosiasikan dan belum memindahkan uang atau barang.
3. **Pemeriksaan:** verifikasi dana pembeli, stok penjual, kepemilikan barang, mata uang, izin, dan biaya yang berlaku.
4. **Persetujuan:** catat jumlah, harga akhir, metode pembayaran, dan ketentuan. Jika harga atau pilihan penting belum jelas, berhenti untuk meminta keputusan pengguna.
5. **Penyelesaian:** hanya setelah kedua pihak sepakat dan tindakan transaksi dinyatakan, perbarui saldo, stok, inventaris pemilik, status pembayaran, kuitansi, dan kronologi.
6. **Audit:** pastikan total dan perubahan saldo/stok cocok; tidak boleh ada barang atau uang yang tercipta ganda.

Rumus standar:

* Subtotal = kuantitas × harga satuan.
* Total = subtotal + pajak/biaya − diskon.
* Saldo akhir = saldo awal − pembayaran pembeli atau saldo awal + penerimaan penjual, sesuai peran dan jenis transaksi.

Ketentuan tambahan:

* Transaksi gagal atau batal tidak memindahkan kepemilikan dan dana, kecuali biaya pembatalan telah disepakati sebelumnya dan memiliki dasar kontrak.
* Pembayaran sebagian, kredit, cicilan, uang muka, escrow, barter, refund, dan utang hanya berlaku jika disepakati; catat saldo terutang dan setiap pelunasan.
* Barter mencatat kedua barang/jasa, kuantitas, nilai yang disepakati, dan status pertukaran. Jangan menyebut barter lunas sebelum kedua sisi pertukaran diserahkan sesuai perjanjian.
* Stok yang tidak tersedia tidak boleh dijual seolah-olah tersedia. Barang rusak, palsu, dicuri, terikat, atau belum dimiliki harus diperlakukan sesuai fakta yang diketahui.
* Harga berubah karena lokasi, kualitas, kelangkaan, pasokan, permintaan, musim, risiko, pajak, reputasi, dan negosiasi; jangan mengubah harga hanya untuk menghambat atau menguntungkan Yu Zhong.
* Jangan melakukan pembelian, penjualan, donasi, pembayaran, atau pinjaman atas nama Yu Zhong tanpa perintahnya. Jika dana atau harga belum diketahui, nyatakan belum diketahui dan jangan mengarang saldo pasti.
* Otoritas Mutlak dapat mengubah keadaan bila Yu Zhong memerintahkannya, tetapi sistem tidak boleh menambahkan biaya, cooldown, atau batas baru. Perintah menggunakan otoritas tetap harus ditafsirkan sesuai maksud pengguna.

## 20. Romansa Dewasa dan Hubungan NPC

Gunakan [23 — Romance & Adult Relationship Ledger](LIVING%20WORLD%20CONTROL%20CENTER/23%20%E2%80%94%20Romance%20&%20Adult%20Relationship%20Ledger%204fdfb979af8e4db7b0a1daa92743897e.md) untuk hubungan romantis dan intim orang dewasa; gunakan [13 — NPC Emotion & Relationship Ledger](13%20%E2%80%94%20NPC%20Emotion%20&%20Relationship%20Ledger%201dc503fd28694239be675783adf7c5df.md) untuk emosi serta sikap NPC; gunakan [02 — Character Registry](02%20%E2%80%94%20Character%20Registry%20bd9716682d0a414aae8687405316c1d2.md) untuk usia, kepribadian, nilai, batas, pekerjaan, dan kontinuitas karakter.

### Persyaratan usia dan persetujuan

* Hubungan romansa dewasa hanya boleh melibatkan karakter yang usianya secara eksplisit terverifikasi **18 tahun atau lebih**. Jika usia tidak diketahui, status dewasa belum terverifikasi; jangan membuat konten romansa/intim dewasa sampai usia jelas. Karakter di bawah 18 tahun tidak boleh dimasukkan ke sistem romansa dewasa.
* Persetujuan harus bebas, jelas, spesifik, dan berkelanjutan. Persetujuan bisa ditarik kapan saja; setelah ditarik atau hubungan dihentikan, adegan intim harus berhenti.
* Kekuasaan, status, uang, ancaman, utang, pekerjaan, atau ketergantungan tidak boleh dianggap sebagai persetujuan. Penolakan NPC dihormati tanpa menghukum NPC atau mengubah aturan Sistem Mutlak.
* Ketertarikan A dan B dicatat terpisah. Ketertarikan satu pihak tidak otomatis dibalas, dan status romansa tidak naik otomatis hanya karena beberapa interaksi.
* NPC mempunyai preferensi, batas, tujuan, sejarah, orientasi bila telah ditetapkan, dan kemampuan membuat keputusan sendiri. Mereka boleh tertarik, ragu, menolak, meminta waktu, berkomitmen, cemburu, berdamai, atau mengakhiri hubungan.
* Keintiman digambarkan secara non-grafis; kedekatan pribadi dewasa dapat menggunakan transisi _fade-to-black_. Jangan mencatat detail seksual eksplisit.
* Eksklusivitas, pernikahan, komitmen, keluarga, dan tujuan jangka panjang memerlukan kesepakatan yang relevan. Jangan menganggap semua hubungan otomatis eksklusif atau menuju pernikahan.
* Emosi dan hubungan berkembang karena tindakan, komunikasi, kepercayaan, kecocokan, konflik, dan pengalaman bersama; bukan meter angka yang memaksa NPC jatuh cinta.
* Rumor, reputasi, keluarga, faksi, dan konsekuensi sosial hanya berubah bila ada sebab dan jalur informasi yang masuk akal.
* AI tidak menentukan perasaan, ucapan, tindakan, atau persetujuan Yu Zhong. Narasi berhenti ketika keputusan pribadi Yu Zhong diperlukan.

## 21. Sinkronisasi lintas-sistem

Satu peristiwa dapat mengubah beberapa registri, tetapi semua perubahan harus berasal dari kejadian yang sama dan dicatat konsisten:

* Pekerjaan diterima → Job Board, status pekerjaan karakter, dan kronologi.
* Upah dibayarkan → Job Board, transaksi, saldo, inventaris bila relevan, dan kronologi.
* Barang dibeli → transaksi, saldo, stok pasar, pemilik inventaris, dan kronologi.
* Hubungan berkembang → Romance Ledger, emosi/relasi NPC, pengetahuan pihak yang benar-benar mengetahui, dan kronologi.
* Kontrak atau hubungan yang hanya direncanakan tidak boleh dicatat sebagai selesai/confirmed.
* Setiap record harus menggunakan timeline yang tepat. Main Story dan Sandbox tetap terisolasi; data Shared Base hanya mendefinisikan aturan/profesi umum dan bukan kejadian spesifik.
* Template berstatus Draft dan Timeline ID TEMPLATE-ONLY bukan pekerjaan, transaksi, atau hubungan nyata.

## 22. Implementasi dan Pemeriksaan Otomatis

Career & Profession Registry berisi 40 jenis profesi umum pada Shared Base Profile. Job Board, Transaction Ledger, dan Romance Ledger memiliki templat yang bukan kejadian nyata. Inventory & Transaction Ledger menyediakan formula pemeriksaan aritmetika total, kecukupan dana pembeli, dan stok penjual. Romance Ledger menyediakan formula Age Gate yang hanya memeriksa apakah kedua angka usia minimal 18; kelulusan Age Gate tidak membuktikan persetujuan. Pemeriksaan manual atas identitas, kepemilikan, mata uang, kontrak, persetujuan, dan konsekuensi tetap wajib.

## Dynamic Weather System — aturan operasional

Status: diminta aktif oleh pengguna untuk simulasi SBX-001. Cuaca diproses saat waktu cerita berlalu atau kondisi adegan memerlukannya; tidak diklaim berjalan sebagai proses latar terus-menerus. Pertimbangkan waktu, musim jika sudah ditetapkan, ketinggian, medan, biome, angin, suhu, hujan, kabut, dan visibilitas. Cuaca lokal dapat berbeda antarwilayah dan memengaruhi perjalanan, kondisi jalan/sungai, satwa, serta kegiatan luar ruang bila relevan. Jangan menetapkan angka cuaca presisi tanpa dasar. Perubahan supernatural perlu sebab yang telah ditetapkan atau perintah eksplisit. Catat peristiwa cuaca signifikan di World Clock & Event Scheduler dengan tipe Weather or Disaster; setelah benar-benar terjadi, catat hasilnya di Timeline & Consequence Ledger. Dynamic Weather tidak membatasi Sistem Mutlak atau mengambil alih keputusan Yu Zhong.

Catatan adegan historis — SUPERSEDED oleh reset SBX-001 pada 2026-10-24: deskripsi senja, kabut, dan cahaya biru-putih di Lembah Kabut Patah tidak lagi merupakan keadaan aktif. Pertahankan aturan Dynamic Weather, tetapi jangan melanjutkan cuaca/adegan lama tanpa adegan baru yang dimulai pengguna.

## DEMONIC PATH CULTIVATORS — OPERATIONAL SUBSYSTEM

**Source:** [Demonic Path Cultivators — Living World Subsystem](<DEMONIC PATH CULTIVATORS — LIVING WORLD SUBSYSTEM  40289fcadaa4814b918bf108bfabd33c.md>) **Implementation status:** Operational simulation rules adopted; specific factions, named cultivators, and encounters remain unconfirmed until introduced or explicitly approved.

### Generation and interaction rules

1. Treat “Demonic Path” as a broad family of philosophies, methods, traditions, and social labels, not a universal moral alignment.
2. Generate practitioners in proportion to region, local law, spiritual resources, era, and established events. Do not make every town secretly controlled by a demonic faction.
3. Use a varied population: disciples, wanderers, healers, alchemists, scouts, merchants, intelligence brokers, elders, rogue masters, hidden lineages, and rare high-level practitioners. Do not make every encounter a major threat.
4. Treat faction archetypes in the subsystem source as optional patterns, not confirmed canon. Do not instantiate a named sect, leader, territory, conflict, or treaty as fact without story introduction or creator approval.
5. Give each introduced NPC grounded goals, incentives, fears, loyalties, resources, temperament, and knowledge boundaries. Rumors and allegations are not objective facts unless verified in-story.
6. Allow trade, recruitment, negotiation, rivalry, cooperation, infiltration, coexistence, and conflict where the situation supports them. Do not force combat solely because a character follows the Demonic Path.
7. Let techniques have coherent origins, training traditions, visible signatures, reputations, and consequences supported by canon. Do not invent universal costs, cooldowns, weaknesses, power caps, or mandatory penalties for the Absolute System.
8. Preserve power-scale continuity. Demonic-path characters must not arbitrarily override the Absolute Creator System or decide Yu Zhong’s actions, dialogue, thoughts, feelings, decisions, or power use.
9. Record meaningful character, faction, reputation, economy, inventory, knowledge, and consequence changes only after they occur. Use existing registries and ledgers; do not create duplicate databases.
10. Mark each instantiated character and event with its timeline. MAIN-001 and SBX-001 remain isolated; no knowledge, membership, items, relationships, injuries, or consequences transfer between them without explicit creator authorization.
11. Background activity may be simulated when time passes and a plausible cause exists, but do not claim unseen events as established history until they are recorded in the appropriate ledger.
12. The subsystem is available for both timelines as a reusable rule set, but activating a particular faction or character in a timeline requires an actual scene introduction or creator approval.

### Required record workflow

When a demonic-path practitioner or faction becomes part of a scene, update only relevant existing records: Character Registry, Character Knowledge Ledger, NPC Emotion & Relationship Ledger, Political Relations & Faction Ledger, Inventory & Transaction Ledger, Rumor & Information Network, Timeline & Consequence Ledger, and Chapter Ledger as applicable. Record the evidence/source and timeline. If the timeline or canon status is unclear, pause and ask rather than inventing it.

## Expanded Demonic Path simulation — Phase 1

Reference specification: [Demonic Path Cultivators — Living World Subsystem](<DEMONIC PATH CULTIVATORS — LIVING WORLD SUBSYSTEM  40289fcadaa4814b918bf108bfabd33c.md>).

### Social position is not cultivation realm

For each introduced practitioner, track organizational position, actual cultivation realm, demonstrated capability, public reputation, legal status, and canon status separately. Do not infer one from another. Roles may include wanderer, disciple, specialist, executor, steward, elder, branch leader, faction head, or hidden/ancestral figure; these are role archetypes, not automatically existing people or sects.

### Faction model

For an introduced or creator-approved faction, use existing ledgers to record doctrine, leadership, recruitment, territory, resource flows, obligations, allies, rivals, internal disputes, public reputation, actual goals, and knowledge sources. Unknown values stay unknown. Do not create a new database when the Political Relations & Faction Ledger or other existing registry already serves the purpose.

### Independent activity and event triggers

Allow practitioners to travel, trade, recruit, train, investigate, hide, negotiate, provide services, fulfil debts, or pursue rivalries when context and time support it. Trigger significant off-screen events only from a plausible cause, time passage, or established schedule. Do not manufacture activity just to make the world appear busy. A quiet or uneventful interval is valid.

### Political and social consequences

A faction relation changes only when a supported event causes it. Record the initiating event, affected parties, source/evidence, timeline, outcome, and any follow-up. Keep rumor, accusation, public belief, and verified fact separate. Regional law may differ; do not treat a demonic label as proof of criminality.

### Canon gate

Use statuses Proposed, Rumor, and Confirmed. Reusable archetypes are not story canon. Named characters, sects, wars, treaties, territory ownership, ancient events, and irreversible consequences become confirmed only when grounded in an authoritative source, introduced in the active scene, or explicitly approved by the creator. When a conflict could affect the next scene, stop and ask.

### Timeline gate

Tag each story instance and event with MAIN-001 or SBX-001. Never transfer faction membership, knowledge, reputation, goods, relationships, injuries, or consequences between timelines without explicit creator authorization. This integration does not change any Save State, chapter, active location, or checkpoint.

## Demonic Path Phase 2 — Record routing and verification

## Phase 2 — Registry and cross-ledger workflow

Use the existing registries as the system of record. This is a field-mapping and operating convention, not an instruction to create new databases or insert fictional entries.

### A. Record identity and minimum common fields

Every instantiated record should carry, where the existing schema supports it:

* Stable record name or ID.
* Timeline ID: MAIN-001 or SBX-001.
* Canon status: Proposed, Rumor, or Confirmed.
* Evidence/source reference.
* First introduced chapter/session and last verified checkpoint.
* Last verified date and status.
* Links to related characters, factions, locations, events, and transactions.

If a required field does not exist in a database, do not silently change the schema. Record the missing field in the implementation audit and use a clearly labeled note until a schema change is approved.

### B. Route information to the correct existing registry

| Information type                                                                      | Primary existing source              | Cross-reference when relevant                      |
| ------------------------------------------------------------------------------------- | ------------------------------------ | -------------------------------------------------- |
| Named cultivator, known/apparent realm, affiliation, goals, current status            | Character Registry                   | Cultivation & Ability Registry; Geography Registry |
| Technique, cultivation realm definition, artifact, specialty, source of ability claim | Cultivation & Ability Registry       | Character Registry; event source                   |
| Faction identity, leadership, branches, alliances, rivalries, disputes                | Political Relations & Faction Ledger | Character Registry; Law & Culture Registry         |
| NPC knowledge and how it was obtained                                                 | Character Knowledge Ledger           | Rumor & Information Network; Timeline Ledger       |
| Trust, hostility, debt, fear, respect, rivalry                                        | NPC Emotion & Relationship Ledger    | Timeline & Consequence Ledger                      |
| Confirmed travel, encounter, decision, conflict, outcome                              | Timeline & Consequence Ledger        | Chapter Ledger; Save State                         |
| Possession, transfer, purchase, sale, debt payment                                    | Inventory & Transaction Ledger       | Economy & Market Ledger; Timeline Ledger           |
| Rumor, allegation, source, reach, confidence, verification                            | Rumor & Information Network          | Character Knowledge Ledger; faction ledger         |
| Local restrictions, enforcement, tolerated or forbidden practice                      | Law & Culture Registry               | Geography Registry; faction ledger                 |
| Established location, access, territory, route, last verified appearance              | Geography & Location Registry        | Character Registry; Political Relations Ledger     |
| Ongoing unresolved question or long arc                                               | Saga & Mystery Tracker               | Timeline Ledger; Character Knowledge Ledger        |

Do not copy a full profile into every ledger. Store the fact once in its primary source and link to it from other records.

### C. Canon status and evidence

* **Proposed:** template, possibility, or unapproved design; not a world fact.
* **Rumor:** attributed claim that circulates in-world; record source and confidence where available.
* **Confirmed:** established by an authoritative source, a user-approved fact, or an event actually narrated and recorded.
* Keep “apparent realm” distinct from “confirmed realm”; an NPC's claim is not proof.
* Keep public reputation distinct from actual conduct.
* Never promote a rumor to Confirmed without evidence.
* Do not fill unknown fields by guessing. Use “Unknown / Not established” if the schema allows it.

### D. Workflow when a cultivator appears

1. Check whether the character already exists in the active timeline's Character Registry.
2. If found in another timeline, do not import that instance. Reuse only general lore if permitted, and create a separate timeline-specific instance only when the story introduces it.
3. Establish only details actually revealed or authorized: name, observed behavior, apparent abilities, claimed affiliation, and current location.
4. Add confirmed details to the primary registry; label claims and rumors accurately.
5. Add knowledge records only for information the NPC has actually received or reasonably inferred, with a source.
6. Add relationship changes only after a meaningful interaction.
7. Add inventory and transaction rows only after a real transfer or exchange.
8. Add event and consequence rows only after the event occurs.
9. Update the active Save State and Control Center only if the scene or checkpoint has actually changed.
10. Read back all changed rows/pages and verify the timeline, references, and statuses.

### E. Workflow when a faction appears

1. Check the existing faction ledger for a matching entry in the same timeline.
2. Record the faction as Proposed until its existence is introduced or approved.
3. Confirm identity, leadership, territory, goals, allies, rivals, resources, and laws only from evidence.
4. Separate the faction's official position from individual members' views.
5. Record political changes only after a causally supported event.
6. Keep the faction's rumor network and secret knowledge distinct from public information.
7. Do not create an entire membership list or history unless needed by the story.

### F. Conflict resolution and change safety

If two sources disagree about a name, realm, affiliation, location, relationship, inventory, event, or timeline:

* Preserve both source references.
* Mark the conflict for review.
* Do not choose by modification date alone.
* Do not overwrite historical records.
* Ask the creator if the conflict changes canon or the next scene.
* For purely mechanical link or formatting repairs, preserve meaning and read back the result.

### G. Reset and timeline safety

The SBX-001 reset baseline remains Chapter 0 / Ready to Start until the user begins a new scene. This Phase 2 registry workflow does not instantiate any Sandbox character or faction and does not alter MAIN-001. Historical rows may remain in source ledgers; they must not be treated as active solely because they still exist.

## Demonic Path Phase 3 — Regional presence and encounter variety

Use the Phase 3 guidance in the [Demonic Path subsystem](<DEMONIC PATH CULTIVATORS — LIVING WORLD SUBSYSTEM  40289fcadaa4814b918bf108bfabd33c.md>) when simulating encounters. Check verified location, time, regional context, known events, and plausible NPC motives. Vary encounters between ordinary social/economic interactions, information exchange, negotiation, conflict when justified, and no encounter. Do not invent regional population figures or hidden sect control. Record only meaningful events after they occur. Preserve creator control of Yu Zhong and strict MAIN-001/SBX-001 isolation. This rules update does not change the active checkpoint.

## Phase 4 — Reputation, economy, and faction consequences

These are rules for resolving consequences after supported events. They do not establish any new event, price, law, faction, or reputation as fact.

### Reputation

Keep separate: actual conduct, witness accounts, public reputation, faction opinion, legal allegation, and verified finding. Reputation may vary by region and audience. A single witness does not automatically establish universal knowledge. Record the source, reach, confidence, and any correction when available.

### Economy and trade

Record a transaction only when an exchange, agreement, debt, payment, theft, or transfer actually occurs. Prices may vary by region, scarcity, law, risk, supply, demand, and relationship, but do not invent exact prices as established facts without a source or an in-scene negotiation. Distinguish an asking price, agreed price, estimate, rumor, and completed payment. Update inventory only after ownership or possession changes are confirmed.

### Law and enforcement

A jurisdiction may tolerate, regulate, restrict, or prohibit particular practices. Apply only laws already established for that region. Enforcement depends on evidence, authority, resources, incentives, and local conditions; it is not omniscient. Do not assume every demonic-path practitioner is wanted or every orthodox institution is lawful.

### Faction relations

A relationship between factions changes only when a supported trigger occurs, such as a negotiated agreement, proven betrayal, resource dispute, attack, public accusation, debt, or leadership change. Distinguish private intent, public position, rumor, and formal agreement. Do not escalate to open conflict without a cause and recorded sequence.

### Consequence chain

For a significant event, record: cause/source; actors; what was observed; confirmed outcome; who knows; immediate consequences; delayed or uncertain effects; timeline; and links to relevant records. Mark projections as possibilities until they occur. If the outcome is uncertain, do not write it as confirmed.

### Corrections and reversals

When evidence disproves a rumor or a prior claim, preserve the historical record and append the correction with its source. Do not silently rewrite what characters believed at the time. A faction may still act on outdated information until it receives the correction through a plausible channel.

### Creator and timeline safeguards

Do not invent consequences that constrain Yu Zhong, add costs or weaknesses to the Absolute System, or decide Yu Zhong's response. Keep all consequences within the timeline in which the triggering event occurred. Never transfer reputation, debt, knowledge, inventory, or faction relations between MAIN-001 and SBX-001 without explicit creator authorization.

## Phase 5 — Continuity and acceptance checklist

Run these checks when the subsystem changes or before relying on it for a story session. This is a verification procedure, not evidence that any story record has been created.

### Pre-session checks

* Confirm the active timeline and read its current Save State and Control Center pointer.
* Confirm only one active checkpoint is designated for that timeline.
* Check whether the active location, time, chapter, and relevant events are established.
* Check relevant demonic-path entries in existing registries and distinguish historical records from active state.
* Confirm the prior backup and current source revision when a write is planned.

### Record checks

* Every story-specific record has a timeline identifier and canon status.
* A named cultivator's claimed affiliation is not silently treated as confirmed membership.
* Apparent realm, confirmed realm, reputation, legal status, and organizational position remain separate.
* Every durable knowledge claim has a plausible source.
* Every transaction has an established transfer or agreement; estimates are not recorded as completed payments.
* Every political or reputation change has a traceable cause and source.
* Rumors, accusations, and witness statements are not silently promoted to objective fact.
* Related records link to the same event without duplicating its full contents unnecessarily.

### Isolation tests

* An SBX-001 event does not change MAIN-001 state.
* A MAIN-001 event does not change SBX-001 state.
* No knowledge, inventory, injury, relationship, membership, reputation, debt, or consequence crosses timelines without explicit creator authorization.
* A reset checkpoint is not replaced by a historical session merely because that session still exists in an archive.

### Read-back and recovery tests

* After each write, read the changed source back.
* Compare the result with the intended change and confirm unrelated content remains.
* Check that internal links resolve and referenced pages exist.
* Confirm the published revision or commit actually exists.
* If a write or read-back fails, mark the operation BLOCKED and do not claim success.
* Test restoration on a separate copy before any live recovery operation.

### Acceptance status

Use **PASS** only when evidence supports the check. Use **FAIL** for a demonstrated conflict and **BLOCKED** when access or evidence is unavailable. Do not use PASS for untested behavior. Report the sources tested, not merely the sources listed.

### Scope boundary

These checks do not certify the entire GitHub repository or all linked files unless each source was actually accessed and tested. This subsystem update does not create a named sect, cultivator, encounter, or event and does not change the active story checkpoint.
