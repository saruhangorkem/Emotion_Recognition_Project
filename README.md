# 🎭 Facial Expression Recognition with CNN (Derin Öğrenme ile Duygu Analizi)

Bu proje, Medeniyet Üniversitesi **Derin Öğrenme** dersi kapsamında geliştirilmiştir. Projenin temel amacı, **FER-2013** veri seti ve **Convolutional Neural Networks (CNN)** mimarisi kullanılarak, anlık kamera görüntüsünden 7 temel duygu durumunu (Mutlu, Üzgün, Kızgın, Şaşkın, Korku, İğrenme, Nötr) tespit etmektir.

## 🚀 Proje Hakkında
* **Geliştirici:** Saruhan Türköz
* **Ders:** Derin Öğrenme
* **Model Doğruluğu (Accuracy):** ~%60
* **Kullanılan Teknolojiler:** Python, TensorFlow/Keras, OpenCV, Gradio

## 📂 Dosya İçeriği
* **`DeepLearning_Proje(1).ipynb`**: Modelin eğitim adımlarını, veri ön işleme süreçlerini ve Gradio arayüz kodlarını içeren Jupyter Notebook dosyası.
* **`duygu_analizi_modeli.h5`**: Eğitilmiş ve ağırlıkları kaydedilmiş CNN model dosyası.
* **`Derin_Ogrenme_Proje_Raporu.pdf`**: Projenin literatür taraması, yöntem açıklamaları ve sonuç analizlerini içeren detaylı rapor.

## 📊 Model Performansı
Modelimiz özellikle **"Mutlu" (%79 F1-Score)** ve **"Şaşkın" (%72 F1-Score)** sınıflarında yüksek başarı göstermiştir. Karmaşıklık matrisi ve detaylı analizler rapor dosyasında mevcuttur.

## 💻 Nasıl Çalıştırılır?
Proje, Google Colab ortamında çalıştırılmaya uygundur.
1. `DeepLearning_Proje.ipynb` dosyasını Colab'de açın.
2. Tüm hücreleri çalıştırın.
3. En altta açılan **Gradio** linkine tıklayarak kamera üzerinden canlı test yapabilirsiniz.

---
