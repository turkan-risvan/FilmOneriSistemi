# Film_Ratings.xlsx dosyası  [Film_Ratings.xlsx](https://github.com/turkan-risvan/FilmOneriSistemi/files/12552561/Film_Ratings.xlsx)

                                                                                                                    
    Öneri Sistemi
→ Veri seti: Film_Ratings.xlsx  

→ Veri kümesinde bir dizi platformunda yayınlanan bazı diziler ve kullanıcıların bunlara verdikleri
puanlar bulunmaktadır.

→ User-User İşbirlikçi tabanlı bir yöntem ile film önermeniz gerekmektedir.

→ Kullanıcıların yaş ve cinsiyet bilgilerini kullanarak benzer kullanıcıları belirlemelisiniz.
  ‘Gender’ sütunu için ‘K’ ve ‘E’ bilgilerini 1 ve 0 ile kodlayın.
  ‘Age’ sütunu için de ayrıklaştırma uygulayın. Örneğin yas<=10→1, 10<yas<=20→2,20<yas<=30→3 gibi

 Yani her bir kullanıcı için 2 özelliğiniz var yas ve cinsiyet. Buna göre her bir kullanıcı 2
sütunlu bir vektör ile temsil edilir.

→ Bir kümeleme algoritması ile benzer kullanıcıları belirleyin. (K-Means, DBSCAN gibi bir
kümeleme algoritması kullanabilirsiniz.)

  Kümeleme algoritmasına bir küme sayısı vermelisiniz.

→ Kendisiyle aynı kümede olan kullanıcılara bir film önerisinde bulunun.
  Örneğin 1. 3. Ve 5. Kullanıcılar aynı kümede ise 1. Kullanıcıya film önermek için, 3. Ve
5. Kullanıcıların izlediği filmlerden en yüksek puanı olanı 1. Kullanıcıya önerin.
 Aynı şekilde diğer kullanıcılar için de bu işlemi yapmalısınız. 19 kullanıcı var her birine
birer tane öneride bulunun.
  Öneride bulunurken ilgili kullanıcının o filmi izleyip izlemediğini kontrol etmelisiniz.
(Eğer puanlama yaptıysa izlemiştir.) Bu durumda bulunduğu kümedeki kullanıcıların
izlediği filmler içinden en yüksek oya sahip 2. Filmi önermelisiniz.
