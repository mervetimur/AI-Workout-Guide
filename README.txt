# AI-Workout-Guide

**Yapay Zeka Destekli Egzersiz Takip ve Yönlendirme Sistemi**

Bu proje, bilgisayarlı görü ve yapay zeka kullanarak kullanıcı hareketlerini gerçek zamanlı analiz eder ve doğru egzersiz formunu sesli olarak geri bildirir.  

# Özellikler

- **Gerçek Zamanlı Analiz:** Kamera üzerinden egzersiz sırasında pozisyon tespiti.
- **Kol ve Bacak Egzersizleri:** Kol ve bacak açısını ölçerek geri bildirim sağlar.
- **Sesli Geri Bildirim:** pyttsx3 ile kullanıcıya doğru form uyarıları verir.
- **Hata Önleme:** Egzersiz sırasında yanlış hareketleri anında bildirir.
- **Kolay Kullanım:** Python ve OpenCV, Mediapipe tabanlı hızlı kurulum.

# Kullanım

1. Python ortamınızı hazırlayın (OpenCV, Mediapipe, pyttsx3 kurulu olmalı).
2. Repo içindeki ana Python dosyasını çalıştırın.
3. Egzersizi seçin: `kol` veya `bacak`.
4. Kamera açılacak ve hareketiniz anlık olarak analiz edilecek.
5. Egzersizi bitirmek için `q` tuşuna basın.

# Gereksinimler

Python 3.8+
OpenCV
Mediapipe
pyttsx3
