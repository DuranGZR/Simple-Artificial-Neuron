# 🧠 Simple Artificial Neuron  
Basit bir yapay nöronun sıfırdan (hiçbir ML kütüphanesi olmadan) nasıl inşa edilip eğitildiğini gösteren mikro proje.  
 — ileri yayılım (forward pass), geri yayılım (backpropagation) ve gradyan inişi (gradient descent) adımlarının nasıl çalıştığını doğrudan görürsün.

---

## 🎯 Projenin Amacı
Bu projenin hedefi, “bir nöron nasıl öğrenir?” sorusuna ezberle değil mantıkla cevap verebilmektir.  
PyTorch veya TensorFlow gibi framework’lerin arka planındaki matematiği **elle** görmek için tasarlanmıştır.  
Her satır eğitim amaçlıdır — üretim için değil, öğrenme için yazılmıştır.

---

## 📁 İçerik
### **Ana Dosya:**
- `micrograd_from_scratch_yay.ipynb`  
  Tek notebook dosyası içinde tüm süreç adım adım ilerler.

---

## ⚙️ Kurulum
Projeyi klonla ve Jupyter Notebook üzerinde çalıştır:

```bash
git clone https://github.com/DuranGZR/Simple-Artificial-Neuron.git
cd Simple-Artificial-Neuron
jupyter notebook micrograd_from_scratch_yay.ipynb
