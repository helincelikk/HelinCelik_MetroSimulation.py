# Metro Simulation

## Proje Açıklaması
Bu proje, bir metro ağı simülasyonu oluşturmak ve belirli istasyonlar arasında en kısa yolu bulmak amacıyla geliştirilmiştir. Şu an için Breadth-First Search (BFS) algoritmasını kullanarak en kısa yolu hesaplayabiliyorum. A* algoritmasını da eklemeyi planlıyorum, ancak henüz tamamlamadım.

## Kullanılan Teknolojiler ve Kütüphaneler
Bu proje Python programlama dili kullanılarak geliştirildi. Kullanılan temel kütüphaneler şunlardır:
- `heapq`: Öncelikli kuyruk yapısı için (A* algoritması eklendiğinde kullanılacaktır).
- `collections`: BFS algoritması için `deque` veri yapısı kullanılmıştır.

## Algoritmaların Çalışma Mantığı
### BFS Algoritması
Breadth-First Search (BFS) algoritması en kısa yolu bulmak için kullanılmıştır. Bu algoritma, graf yapısında düğümleri genişlik öncelikli olarak ziyaret ederek en kısa yolu belirler.

1. Başlangıç düğümü kuyruğa eklenir.
2. Kuyruk boşalana kadar şu işlemler yapılır:
   - Kuyruğun başındaki düğüm çıkarılır.
   - Komşu düğümler kontrol edilir.
   - Daha önce ziyaret edilmemiş düğümler kuyruğa eklenir.
3. Hedef düğüme ulaşıldığında en kısa yol bulunmuş olur.

### A* Algoritması (Henüz Eklenmedi)
İlerleyen aşamalarda A* algoritmasının da eklenerek daha optimize bir yol bulma yöntemi sağlanması planlanmaktadır.

## Örnek Kullanım ve Test Sonuçları
Proje, belirli metro istasyonları arasındaki en kısa yolu hesaplamak için kullanılmaktadır. Kullanıcı başlangıç ve bitiş istasyonlarını girdikten sonra BFS algoritması en kısa yolu belirleyerek sonucu ekrana yazdırmaktadır.

## Projeyi Geliştirme Fikirleri
- A* algoritmasının eklenmesi.
- Kullanıcı dostu bir arayüz geliştirilmesi.
- Farklı şehirlerin metro ağlarının projeye entegre edilmesi.
- Trafik yoğunluğu gibi dinamik değişkenlerin dahil edilmesi.

Bu proje GitHub üzerinden paylaşılacak ve geliştirilmeye devam edilecektir.
