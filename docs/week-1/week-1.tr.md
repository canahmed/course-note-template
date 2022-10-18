---
marp: true
theme: default
style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Örnek Ders Adı'
footer: '![height:50px](http://erdogan.edu.tr/Images/Uploads/MyContents/L_379-20170718142719217230.jpg) RTEU CE204 Hafta-1'
title: "Örnek Ders Adı"
author: "Author: Dr. Öğr. Üyesi Uğur CORUH"
date:
subtitle: "Örnek Ders Modülü Adı"
geometry: "left=2.54cm,right=2.54cm,top=1.91cm,bottom=1.91cm"
titlepage: true
titlepage-color: "FFFFFF"
titlepage-text-color: "000000"
titlepage-rule-color: "CCCCCC"
titlepage-rule-height: 4
logo: "assets/2021-10-19-15-01-36-image.png"
logo-width: 100 
page-background:
page-background-opacity:
links-as-notes: true
lot: true
lof: true
listings-disable-line-numbers: true
listings-no-page-break: false
disable-header-and-footer: false
header-left:
header-center:
header-right:
footer-left: "© Dr. Öğr. Üyesi Uğur CORUH"
footer-center: "License: WTFPL"
footer-right:
subparagraph: true
lang: en-US 

math: katex
---

<!-- _backgroundColor: aquq -->

<!-- _color: orange -->

<!-- paginate: false -->

## Python Programlamaya İlk Adım

### Hafta-1 (Python Nasıl Kullanılır: İlk Adımlarınız)

#### Bahar Dönemi, 2022-2023

İndir [DOC](week-1.tr.md_doc.pdf), [SLIDE](week-1.tr.md_slide.pdf), [PPTX](week-1.tr.md_slide.pptx)

<iframe width=700, height=500 frameBorder=0 src="../week-1.tr.md_slide.html"></iframe>

---

<!-- paginate: true -->

### Anahat

- Python nedir ve neden kullanmalısınız?
- Python Nasıl İndirilir ve Kurulur?
- Temel Python Sözdizimi

---

## **Python Programlamaya İlk Adım**

---

### Python Programlamaya İlk Adım

- **Neden Python Kullanmalısınız?**
Adını İngiliz komedi grubu Monty Python'dan alan Python, üst düzey, yorumlanmış, etkileşimli ve nesne yönelimli bir programlama dilidir. Esnekliği, hem büyük hem de küçük birçok şeyi yapmanızı sağlar. Python ile temel programlar ve komut dosyaları yazabilir ve ayrıca karmaşık ve büyük ölçekli kurumsal çözümler oluşturabilirsiniz.
   - Bilgisayar programlama dünyasının her yerinde Python'u bulabilirsiniz. Örneğin Python, Reddit, Dropbox ve YouTube gibi dünyanın en popüler web sitelerinden bazılarının temelidir. Python web çerçevesi Django, hem Instagram'a hem de Pinterest'e güç sağlar.
---



- **Python, diğer programlama dilleriyle karşılaştırıldığında aşağıdaki özelliklere sahiptir:**
Yorumlandı: Derlenmiş dillerden daha taşınabilir ve denemesi daha hızlıdır.
Multiparadigma: Nesne yönelimli, zorunlu ve işlevsel stil dahil olmak üzere farklı stillerde kod yazmanıza olanak tanır.
Dinamik olarak yazılmış: Değişken türlerini çalışma zamanında kontrol eder, bu nedenle bunları açıkça bildirmeniz gerekmez.
Güçlü bir şekilde yazılmış: Uyumsuz türlerde güvenli olmayan işlemlerin fark edilmemesine izin vermez.

![center h:300px](assets/en-populer-programlama-dili-python-oldu-techinside-730x480%20(1).jpg)

---
Python, Linux, Mac, Windows ve diğer birçok platformda çalışır. MacOS'ta ve çoğu Linux dağıtımında önceden yüklenmiş olarak gelir. Ancak, güncel olmak istiyorsanız, muhtemelen en son sürümü indirip yüklemeniz gerekir.


- **Python Nasıl İndirilir ve Kurulur:**
Python, Linux, Mac, Windows ve diğer birçok platformda çalışır. MacOS'ta ve çoğu Linux dağıtımında önceden yüklenmiş olarak gelir. Ancak, güncel olmak istiyorsanız, muhtemelen en son sürümü indirip yüklemeniz gerekir.

![bg right:50% h:400px](assets/python.jpg)

---

**İşletim sisteminizde genel olarak hangi Python sürümünün kurulu olduğunu kontrol etmek için terminali veya komut satırını açın ve aşağıdaki komutu çalıştırın:**

Bu komut, sisteminizin varsayılan Python 3 kurulumunun sürümünü yazdırır. Bazı işletim sistemleri varsayılan Python yüklemeleri olarak Python 2'yi içerdiğinden, python yerine python3 kullandığınızı unutmayın.

![bg left:50% h:80px](assets/How%20to%20Use%20Python_%20Your%20First%20Steps%20%E2%80%93%20Real%20Python%20-%20Google%20Chrome%2018.10.2022%2018_07_44.png)

---




![bg h:px](assets/python.png)

---


- **Temel Python Sözdizimi:**
Python sözdizimi açık, özlü ve okunabilirliğe odaklanmıştır. Okunabilirlik, tartışmasız dilin kendisinin daha çekici özelliklerinden biridir. Python'u programlamayı öğrenen insanlar için ideal kılar. Bu bölümde Python sözdiziminin birkaç önemli bileşeni hakkında bilgi edineceksiniz:


![bg left:50% h:500px](assets/4c3f773df01c4ca71849ea0814b62c4adfa142dc.webp)

---



- **YORUMLAR:**
Yorumlar, kodunuzda yaşayan ancak kodu yürütürken Python yorumlayıcısı tarafından yok sayılan metin parçalarıdır. Siz ve diğer geliştiriciler, kodun ne yaptığını veya kodun neden belirli bir şekilde yazıldığını hızlı bir şekilde anlayabilmeniz için kodu açıklamak için yorumları kullanabilirsiniz. Python'da yorum yazmak için yorum metninizin önüne bir kare işareti (#) eklemeniz yeterlidir:


![bg left:50% h:80px](assets/6.png)

---

**BİRDAHAKİ DERS GÖRÜŞMEK ÜZERE:)**

---

**YAPILACAKLAR** KURS NOTLARINIZ İÇİN İÇERİĞİ GÜNCELLEME

--- 

## Referanslar

- https://realpython.com/python-first-steps/#the-basic-python-syntax
- https://www.techinside.com/en-populer-programlama-dili-python-oldu/
- https://www.abakuskitap.com/blog/icerik/python-ile-ne-yapabilirsiniz-pythonin-3-temel-kullanim-alani
- https://www.fiverr.com/fatihagirtmis/do-python-programming-for-you



