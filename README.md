# AlgoViz Pro - Kapsamlı Algoritma Görselleştirme ve Eğitim Platformu 🚀💜

**AlgoViz Pro**, bilgisayar bilimleri ve yazılım mühendisliği öğrencileri için tasarlanmış, 60'tan fazla algoritmayı gerçek zamanlı animasyonlarla sunan, etkileşimli bir eğitim uygulamasıdır. Proje, karmaşık matematiksel kavramları ve veri yapılarını herkes için anlaşılır kılmayı hedefler.

## ✨ Öne Çıkan Özellikler

* **Gerçek Zamanlı Görselleştirme:** Algoritmaların çalışma mantığını `CustomPaint` ve `Canvas API` kullanarak adım adım animasyonlarla gösterir.
* **İnteraktif Kod Tamamlama (Code Challenge):** Eksik kod bloklarını sürükle-bırak yöntemiyle tamamlayarak algoritma mantığını pekiştirin.
* **Sandbox Modları:** Kendi graflarınızı ve veri setlerinizi oluşturup algoritmaları bu veriler üzerinde test edin.
* **Oyunlaştırma (XP & Seviye):** Görevleri tamamladıkça XP kazanın ve seviye atlayın.
* **Erişilebilirlik:** TTS (Text-to-Speech) desteği ile algoritma adımlarını sesli dinleme imkanı.

---

## 🛠️ Teknik Mimari ve Teknoloji Yığını

Uygulama, **Flutter 3.x** ve **Dart** diliyle modüler bir yapıda inşa edilmiştir:

* **Durum Yönetimi:** `Provider` (MultiProvider yapısı) ile verimli state yönetimi.
* **Veri Depolama:** `SharedPreferences` ile yerel ayar, kullanıcı tercihlerini ve XP ilerlemesini kalıcı tutma.
* **Reklam Entegrasyonu:** `Google Mobile Ads` (Interstitial ve Rewarded) ile sürdürülebilir gelir modeli.
* **Grafik Motoru:** Düşük seviyeli çizimler için `Custom Paint` ve `Canvas API`.

---

## 📚 Desteklenen Algoritma Kütüphanesi

### 1. Sıralama ve Arama (Sorting & Searching)
* **Temel Yöntemler:** Bubble, Selection, Insertion Sort (Karşılaştırmalı mantık).
* **Böl ve Yönet:** Quick Sort, Merge Sort (Divide & Conquer).
* **İleri Seviye:** Heap, Radix, Counting ve Bucket Sort (Karşılaştırmasız teknikler).
* **Arama:** Binary Search, Linear Search simülasyonları.

### 2. Graf Teorisi ve Arama (Graph Algorithms)
* **Yol Bulma:** Dijkstra, A*, BFS, DFS, Bellman-Ford, Floyd-Warshall.
* **Ağ Tasarımı:** Minimum Kapsayan Ağaç (Prim, Kruskal), Topolojik Sıralama, Tarjan (SCC).
* **Akış Analizi:** Edmonds-Karp, Dinic, Maksimum Akış.

### 3. Veri Yapıları ve Ağaçlar (Data Structures)
* **Gelişmiş Ağaçlar:** AVL Tree, Red-Black Tree, B-Tree, Trie, Max/Min Heap.
* **Özel Yapılar:** Segment Tree, Fenwick Tree, Hash Table, DSU (Disjoint Set Union), Bloom Filter, Skip List.

### 4. Yapay Zeka ve Veri Madenciliği (AI & ML)
* **Öğrenme Modelleri:** Yapay Sinir Ağları (MLP), Perceptron, Q-Learning (Pekiştirmeli Öğrenme), Genetik Algoritmalar.
* **İstatistiksel Analiz:** K-Means, KNN, Naive Bayes, Lojistik ve Lineer Regresyon.
* **Veri Madenciliği:** DBSCAN, Apriori, Karar Ağaçları, Random Forest, PCA, t-SNE.

### 5. Kriptografi, Matematik ve Sistem
* **Güvenlik:** RSA (Şifreleme/Çözme kanıtları), SHA-256, Diffie-Hellman Key Exchange.
* **Matematik:** FFT (Hızlı Fourier Dönüşümü), Öklid (EBOB), Eratosthenes Kalburu, Graham Scan (Convex Hull).
* **İşletim Sistemleri:** CPU Scheduling (FCFS, SJF, Round Robin), Page Replacement (FIFO, LRU, Optimal).

**Geliştirici:** [Elif Nur Ayhan](https://github.com/ElifNur06)  
**Tarih:** Nisan 2026
