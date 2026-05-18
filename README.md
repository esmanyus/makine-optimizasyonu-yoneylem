# Yöneylem Araştırması - Makine Satın Alma Optimizasyonu

Bu proje, bir şirketin bütçe, fabrika alanı ve operatör sayısı kısıtları altında saatlik kârını enbüyükleyen (maksimize eden) **Doğrusal Programlama** ve **Tam Sayılı Doğrusal Programlama** modelini içermektedir.

## 📊 Proje İçeriği
* `makine_verileri.xlsx`: Probleme ait tüm bütçe, alan, kâr ve makine parametrelerini içeren veri dosyası.
* `machine_optimization.ipynb`: Verileri Excel'den okuyup modelleyen ve `scipy.optimize.linprog` kütüphanesi kullanarak çözen Jupyter Notebook dosyası.

## 🛠️ Kullanılan Teknolojiler
* Python 3
* Scipy (Optimizasyon için)
* Pandas & OpenPyxl (Excel veri yönetimi için)
