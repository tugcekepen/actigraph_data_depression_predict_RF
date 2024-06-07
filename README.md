Veri setini indirmek için: https://www.kaggle.com/datasets/arashnic/the-depression-dataset

Depresyon tahmini için veri setindeki koşul grubuna ait MADRS1 puanları kullanılmış olup
koşul grubundaki her bir kişinin ölçüm gün sayısı (scores.csv, "days" sütunu) kadar tutular aktivite kayıtlarının (condition klasöründeki her bir dosyanın "activity" sütunu) ortalaması alınarak modeller eğitilmiştir.

Lineer Regresyon ile deneme amaçlı ilerlendi ve modelin veri setine uyumlu olmadığı görüldü. R² değeri -593.9413516240888

Random Forest Regresyon ile koşul grubunun ortalama aktiviteleri, cinsiyetleri, ölçüm gün sayıları ve yaşları özellik olarak alınarak MADRS1 puanları ile eğitildiğinde
kontrol grubu için yapılan tahminlerin R2 değeri 0.757 olarak bulunmuştur.
