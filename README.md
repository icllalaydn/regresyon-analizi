HTML dosyamı GitHub Pages üzerinden görmek için [buraya tıklayın](https://icllalaydn.github.io/regresyon-analizi/regresyon_analızı.html).

## Regresyon Analizi Projesi: Öğrenci Başarısının Tahmini

Bu proje, öğrencilerin final notlarını (G3) tahmin etmek amacıyla bir regresyon modeli oluşturmayı ve bu modelin varsayımlarını test etmeyi hedeflemektedir. Veri seti olarak `student_data.csv` kullanılmıştır.

### Amaç
Öğrencilerin final notlarını (G3) bağımlı değişken olarak alarak, diğer değişkenlerle (G1, G2, studytime, absences, failures) arasındaki ilişkiyi analiz etmek ve bir regresyon modeli kurmak.

### Kullanılan Yöntemler
1. **Veri Analizi**: Veri setinin özet istatistikleri ve eksik gözlem kontrolü yapıldı.
2. **Regresyon Modeli**: `lm()` fonksiyonu kullanılarak bir doğrusal regresyon modeli kuruldu.
3. **Varsayım Testleri**:
   - **Normallik Varsayımı**: QQ plot ve Shapiro-Wilk testi ile kontrol edildi.
   - **Değişen Varyans**: Breusch-Pagan ve White testleri uygulandı.
   - **Aykırı Değerler**: Leverage, studentize artıklar ve Cook's distance metrikleri kullanıldı.
   - **Çoklu Doğrusallık**: Korelasyon matrisi, VIF ve koşul indeksi ile değerlendirildi.
4. **Model Performansı**: Veri seti eğitim ve test olarak ayrılarak model performansı karşılaştırıldı.

### Kullanılan Paketler
- `ggplot2`, `olsrr`, `lmtest`, `faraway`, `car`, `corrplot`, `fpp2`


## Nasıl Çalıştırılır?
1. R Studio'yu açın.
2. `regresyon_ödev1.Rmd` dosyasını yükleyin.
3. Gerekli paketlerin yüklü olduğundan emin olun.
4. R Markdown dosyasını "Knit" butonu ile çalıştırın.

## Katkıda Bulunma
Bu proje açık kaynaklıdır. Katkıda bulunmak için fork edip pull request gönderebilirsiniz.
