# 🧠 Notionary: Semantic Memory Engine

Notionary, dijital not alma alışkanlıklarını kökten değiştirmeyi hedefleyen, metinleri anlamsal (semantic) bağlamlarına göre analiz edip organize eden bir **Yapay Zeka Hafıza Motorudur.** Bu proje, notları sadece depolamak yerine onları birer "anlamsal hücre" olarak görür ve aralarındaki gizli bağlantıları matematiksel olarak ortaya çıkarır.

---

## 🚀 Temel Özellikler

* **Semantic Embedding:** Notları **SBERT (all-MiniLM-L6-v2)** mimarisiyle 384 boyutlu vektörlere dönüştürerek kavramsal anlamlarını yakalar.
* **Intelligent Clustering:** **HDBSCAN** ve **UMAP** kullanarak notları doğal dağılımlarına göre gruplandırır.
* **Auto-Labeling System:** **TF-IDF** ve ön tanımlı kategori haritaları sayesinde klasörleri içeriğe uygun şekilde otomatik isimlendirir.
* **Knowledge Visualization:** Karmaşık bilgi yapılarını 2D düzleme indirgeyerek görsel bir **"Bilgi Haritası"** sunar.

---

## 🛠️ Kurulum

Sistemi kendi bilgisayarınızda çalıştırmak için öncelikle depoyu klonlayın ve gerekli bağımlılıkları yükleyin:

    git clone https://github.com/emrehansaglam/notionary.git
    cd notionary
    pip install -r requirements.txt

---

## ⚙️ Teknik Altyapı

* **NLP:** `sentence-transformers`, `nltk`
* **Clustering & Dim. Reduction:** `hdbscan`, `umap-learn`, `scikit-learn`
* **Data Processing & Visualization:** `pandas`, `matplotlib`, `seaborn`

---

## 👤 Geliştirici

Bu proje **Emrehan Sağlam** tarafından geliştirilmiştir.

* **LinkedIn:** [Emrehan Sağlam](https://www.linkedin.com/in/emrehan-sa%C4%9Flam-710705340/)
* **GitHub:** [github.com/emrehansaglam](https://github.com/emrehansaglam)

---

## 📄 Lisans

Bu proje **MIT Lisansı** altında korunmaktadır. Kaynak gösterilerek kullanılabilir ve geliştirilebilir.

---
*© 2026 | Emrehan Sağlam*
