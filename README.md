# ExplainableAi

## Diyabet Verisi ile Model Yorumlama: SHAP ve LIME Uygulamaları

Bu proje, makine öğrenimi modellerinin karar verme süreçlerini daha anlaşılır ve şeffaf hale getirmek amacıyla oluşturulmuştur. SHAP (SHapley Additive Explanations) ve LIME (Local Interpretable Model-Agnostic Explanations) yöntemleri, diyabet veri seti üzerinde uygulanarak modellerin yorumlanabilirliğine dair karşılaştırmalı bir analiz sunulmaktadır.

---

## 📊 Kullanılan Veri Seti

- **Dosya Adı:** `diabetes.csv`  
- **Kaynak:** PIMA Indian Diabetes veri seti  
- **Özellikler:** Yaş, gebelik sayısı, kan basıncı, glikoz düzeyi, BMI vb.  
- **Amaç:** Diyabet teşhisine yönelik bir sınıflandırma modeli geliştirmek ve bu modelin tahminlerini açıklamak.

---

## 🧭 Proje Yapısı
. ├── shapWith_diabetsData/ 
  │ ├── diabetes.csv 
  │ └── shap_notebook.ipynb 
  │ ├── limeWith_diabetsData/ 
  │ ├── diabetes.csv 
  │ └── lime_notebook.ipynb 
  │ └── README.md



## 📂 Klasör Açıklamaları

### 📁 `shapWith_diabetsData/`
Bu klasörde, SHAP yöntemi kullanılarak modelin hem genel (global) hem de örneğe özel (lokal) kararlarının yorumlanması gerçekleştirilmiştir. Özelliklerin model kararlarına katkısı grafiksel olarak sunulmuştur.

### 📁 `limeWith_diabetsData/`
Bu klasörde, LIME yöntemi ile tekil gözlemler üzerinden modelin nasıl tahminlerde bulunduğu açıklanmıştır. Lokal analizlerle belirli bir tahminin altında yatan nedenler detaylandırılmıştır.

---

## 🎯 Projenin Amacı

Bu çalışma, makine öğrenimi modellerini yalnızca doğruluk oranları üzerinden değil, aynı zamanda **yorumlanabilirlik ve şeffaflık açısından da değerlendirmeyi** hedeflemektedir. SHAP ve LIME gibi açıklanabilir yapay zeka teknikleri, kullanıcı güvenini artırmak ve modellerin karar süreçlerini daha anlaşılır hale getirmek açısından kritik öneme sahiptir.

---

## 📌 Notlar

- Her klasör kendi içerisinde bağımsız olarak çalışabilir durumdadır.
- Her bir klasörde veri seti (`diabetes.csv`) ve ilgili Jupyter Notebook dosyaları yer almaktadır.
- Not defterleri doğrudan çalıştırılabilir yapıdadır.
