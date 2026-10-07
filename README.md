# 🧭 Maze Pathfinding Visualizer

Interactive Maze Pathfinding Visualizer berbasis HTML, CSS, dan JavaScript untuk mempelajari serta membandingkan berbagai algoritma pencarian rute pada grid maze.

Project ini menampilkan proses pencarian secara visual, termasuk node yang sedang diperiksa, frontier, node yang sudah dikunjungi, hingga rute akhir. Setiap algoritma juga dilengkapi dengan rumus dan live calculation log sehingga cocok digunakan sebagai media pembelajaran algoritma pencarian.

## 🚀 Live Demo

🔗 [Coba Maze Pathfinding Visualizer](https://bahrizalmulyawan.github.io/patchfiner/Index.html)

Tidak perlu instalasi. Buka link di atas untuk langsung mencoba visualizer di browser.

## ✨ Features

- 🧠 **10 algoritma pathfinding**
  - Dijkstra
  - A*
  - Breadth-First Search (BFS)
  - Blind Search / Depth-First Search (DFS)
  - Greedy Best-First Search
  - Bidirectional BFS
  - Bidirectional Dijkstra
  - Bidirectional A*
  - Uniform Cost Search (UCS)
  - IDA*

- 🗺️ **Interactive maze**
  - Tambah/hapus wall secara manual
  - Pindahkan posisi Start
  - Pindahkan posisi Goal
  - Generate maze secara otomatis
  - Reset grid

- 📊 **Live statistics**
  - Algoritma yang digunakan
  - Jumlah node yang diperiksa
  - Panjang rute
  - Status pencarian

- 🧮 **Live formula & calculation log**
  - Menampilkan proses perhitungan algoritma
  - Menampilkan nilai `g(n)`, `h(n)`, `f(n)` dan distance sesuai algoritma
  - Menampilkan langkah pembentukan path

- 🌐 **Bilingual UI**
  - Bahasa Indonesia
  - English

- 🌙 **Light / Dark Mode**
  - Tema disimpan menggunakan `localStorage`

- 📱 **Responsive design**
  - Dapat digunakan pada desktop maupun perangkat mobile

- ⚡ **Adjustable animation speed**
  - Super cepat
  - Cepat
  - Normal
  - Lambat

## 🧠 Algorithms

| Algorithm | Strategy |
|---|---|
| Dijkstra | Memilih node dengan distance terkecil |
| A* | `f(n) = g(n) + h(n)` |
| BFS | FIFO Queue, eksplorasi level demi level |
| Blind Search / DFS | Stack LIFO / DFS |
| Greedy Best-First | Memilih heuristic terkecil |
| Bidirectional BFS | Pencarian dari Start dan Goal |
| Bidirectional Dijkstra | Dijkstra dari dua arah |
| Bidirectional A* | A* dari dua arah |
| UCS | Memilih `g(n)` terkecil |
| IDA* | DFS dengan threshold yang meningkat |

## 🎮 How to Use

1. Pilih algoritma yang ingin digunakan.
2. Pilih ukuran maze.
3. Klik **Generate Maze** atau buat wall secara manual.
4. Jika diperlukan, ubah posisi Start dan Goal.
5. Atur kecepatan animasi.
6. Klik **Mulai**.
7. Amati proses pencarian dan hasil path pada grid.
8. Gunakan bagian CLI / Live Formula untuk melihat proses perhitungan algoritma.

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- DOM API
- LocalStorage

Tidak membutuhkan framework maupun dependency eksternal.

## 🚀 Getting Started

### Clone repository

```bash
git clone https://github.com/bahrizalmulyawan/patchfinder-visualizer.git
```

### Masuk ke directory

```bash
cd patchfinder-visualizer
```

### Jalankan aplikasi

Buka file berikut menggunakan browser modern:

```text
index.html
```

Atau langsung gunakan [Live Demo](https://bahrizalmulyawan.github.io/patchfiner/patchfinder.html).

## 📁 Project Structure

Project dibuat sebagai single-file web application yang berisi HTML, CSS, dan JavaScript.

```text
patchfinderv1/
patchfinderv2
└── index.html
```

## 🎓 Educational Purpose

Project ini dibuat sebagai media visualisasi untuk membantu memahami bagaimana algoritma pencarian bekerja pada sebuah grid.

Dengan membandingkan berbagai algoritma, pengguna dapat mengamati perbedaan:

- Strategi eksplorasi
- Penggunaan heuristic
- Jumlah node yang diperiksa
- Panjang path
- Arah pencarian
- Proses pembentukan route
- Proses evaluasi node

Project ini cocok digunakan sebagai media pembelajaran untuk topik:

- Artificial Intelligence
- Graph Search
- Pathfinding
- Search Algorithms
- Heuristic Search

## 🤝 Contributing

Pull request dan improvement sangat terbuka.

1. Fork repository.
2. Buat branch baru:

```bash
git checkout -b feature/new-feature
```

3. Lakukan perubahan.
4. Commit:

```bash
git commit -m "Add new feature"
```

5. Push branch:

```bash
git push origin feature/new-feature
```

6. Buat Pull Request.

## 📄 License

Tambahkan license yang sesuai dengan kebutuhan project.

Jika menggunakan MIT License, tambahkan file `LICENSE` pada root repository.

## 👨‍💻 Author

**Bahrizal Mulyawan**

- GitHub: [@bahrizalmulyawan](https://github.com/bahrizalmulyawan)
- Live Demo: [Maze Pathfinding Visualizer](https://bahrizalmulyawan.github.io/Patchfiner/Index.html)

---

⭐ Jika project ini membantu pembelajaran algoritma pathfinding, jangan lupa beri **Star** pada repository!
