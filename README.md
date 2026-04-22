📊 Law of Large Numbers Simulation

📌 Proje Açıklaması
Bu proje, Büyük Sayılar Yasası’nı (Law of Large Numbers) simülasyonlar ile gözlemlemek için geliştirilmiştir.

Rastgele deneyler yapılarak (zar atma, yazı-tura ve binom dağılımı), örneklem ortalamalarının teorik değerlere nasıl yaklaştığı analiz edilmiştir.

 🎯 Amaç
- Rastgele deneylerin uzun vadede sabit değerlere yakınsadığını göstermek
- Olasılık teorisini görselleştirmek
- Simülasyon ile istatistiksel davranışı incelemek

🧪 Kullanılan Deneyler

🎲 Zar Deneyi
- 1 ile 6 arasında rastgele sayılar üretildi
- Teorik ortalama: **3.5**

🪙 Yazı-Tura Deneyi
- 0 ve 1 üretildi
- Teorik ortalama: **0.5**

📊 Binom Deneyi
- n = 10, p = 0.7
- Teorik ortalama: **7**

 📦 Kullanılan Teknolojiler
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

📈 Sonuç
Tüm deneylerde örneklem sayısı arttıkça ortalama değerlerin teorik değerlere yakınsadığı gözlemlenmiştir. Bu durum Büyük Sayılar Yasası’nı doğrulamaktadır.


🚀 Nasıl Çalıştırılır
```bash
pip install numpy matplotlib notebook
jupyter notebook
