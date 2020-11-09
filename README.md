# Heart_Fail_Data_Analysis
Kalp Yetmezliği Tahmini 
Veri seti kalp yetmezliğine bağlı olabilecek 12 değişkeni içermektedir.
Amaç kalp yetmezliğine bağlı ölümleri tahmin etmek için belirlenen 12 değişken ile makina öğrenmesi algoritması geliştirmek.
Bu değişkenler :
Hedef Değişkeni > DEATH_EVENT (0: No , 1:Yes)
Yaş (age)
Anemi (anemia 0:No , 1:Yes)
Kreatinin fosfokinaz (creatinine_phosphokinase 0:No , 1:Yes)
Diyabet (diabetes 0:No , 1:Yes)
Ejeksiyon fraksiyonu (ejection_fraction)
Yüksek tansiyon (high_blood_pressure 0:No , 1:Yes)
Trombositler (platelets)
Serum kreatinin (serum_creatinine)
Serum sodyum (serum_sodium)
Cinsiyet (sex 0: Female , 1: Male)
Sigara kullanımı (smoking 0:No , 1:Yes)
Zaman (time)

Veriye makina öğrenmesi algoritmaları iki aşamada uygulanarak sonuçlar elde edilmiştir. 
İlk aşamada tüm parametrelerle eleme yapılmaksızın modeller eğitilmiş ikinci aşamada ise lojistik regresyon çıktısı incelenerek anlamsız parametereler veri setinden çıkarılıp modeller eğitilmiştir. Aynı zamanda ilk aşama uygulanırken parametrelere standart scaler işlemi uygulanmış en iyi sonuç alınacak şekilde düzenlemeler yapılmıştır.

Her iki aşamaya uygulanan algoritmalar sonucunda en yüksek accuracy score SVC algoritmasıyla 79.7980% olarak bulunmuştur.
En iyi ikinci accuracy score ise Random Forest algoritması ile 76.7677% bulunmuştur.

