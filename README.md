# Foggos - Java Dungeon Game

**Foggos** adalah game 3D dungeon crawler sederhana berbasis Java dengan tampilan perspektif orang pertama. Menggunakan teknik **raycasting**, pemain harus menjelajahi penjara gelap, menghindari dan melawan monster, serta mencari jalan keluar dengan mengumpulkan item seperti kunci.

## 🎮 Features

- First-person 3D view menggunakan raycasting.
- Battle system berbasis turn-based.
- Audio effects & background music (can be toggled ON/OFF).
- Interactive elements seperti kunci dan pintu terkunci.
- Ending scene saat pemain menyelesaikan dungeon.

## 🕹️ Kontrol

| Tombol | Fungsi                 |
|--------|------------------------|
| W      | Jalan maju             |
| A      | Putar ke kiri          |
| D      | Putar ke kanan         |
| S      | Putar ke belakang      |
| E      | Interaksi              |
| 1      | Attack (dalam battle)  |
| 2      | Heal (gunakan potion)  |
| 3      | Run (kabur dari battle)|

## 📁 Struktur Folder

```bash
src/
├── Core/           # Main game logic
├── Entity/         # Entity classes (Player, Monster)
├── Inputs/         # Input handlers, audio, texture loader
├── Resource/       # Gambar dan suara untuk game
└── MainRun.java    # Entry point
```

## ▶️ Cara Menjalankan

1. Pastikan JDK sudah terpasang.
2. Compile dan jalankan dengan terminal:

```bash
javac -d bin src/**/*.java
java -cp bin Core.MainRun
```

Atau gunakan IDE seperti IntelliJ / Eclipse.

## 👨‍💻 Developer Team
Game ini dikembangkan oleh:

Irvandi Ramadhan Abbas – Analyst

M Qodratul Qudus – Designer

Rijan Ananta – Manager

## 📜 License
Game ini dibuat untuk tujuan pembelajaran. Anda bebas menggunakan dan mengubahnya untuk keperluan non-komersial dengan mencantumkan kredit.