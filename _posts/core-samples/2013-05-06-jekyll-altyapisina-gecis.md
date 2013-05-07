---
layout: post
category : 
tagline: ""
tags : [jekyll, ruby, blog]
---
{% include JB/setup %}

Aslında çok uzun sayılmasada bir süredir blog yazıyordum.Genellikle teknik yazılar (edindiğim tecrübeler , karşılaştığım sorunlar vs vs)yazdığım bu blog Natro Hosting de barınıyordu.Bi sabah yeni bir yazı daha yazmak istediğimde trajikomik bir manzara ile karşılaştım Hacker Okan adlı vatandaş sitemi hacklemiş(?) içierisinde resmi olan bir index atmış.Veritabanını silmemişti ben natro hostingin berbat ötesi hizmetine kızıp kendim sildim tüm bilgileri. Sorun kullandığım wordpress alt yapısındamı yoksa natro hostingtemiydi tam bilmiyorum (açıkçası ilgilenmedim indexi görünce güldüm ve kapattım).Zaten çok yavaş çalışan Natro ve gereksiz özellikleri olan Wordpress alt yapısından sıkılmaya başlamış alternatifler arıyordum ve sonunda bende herkes gibi jekyll alt yapısını kullanmaya ve blogumu github ta host etmeye başladım.

Jekyll alt yapısından kısaca bahsetmek gerekirse;

Jekyll  Ruby ile geliştirilmiş statik bir site üreticisidir.Herhangi bir yönetim paneli yada veritabanı bulunmuyor siz yazılarınızı Markdown formatında hazırlıyorsunuz jekyll sizin için html sayfalarına dönüştürüyor.Bu durumda wordpress yönetim paneli ile uğraşmaktansa kullandığım editör ile yazı yazabiliyor olmak bana daha rahat geliyor. 

Hosting işlemini github üzerinden yapabiliyorsunuz. Öncelikle username.github.com şeklinde bir repo oluşturup sonrasında jekyll dosyalarını forklamanız gerekiyor. Tabi sonrasında config.yml dosyasından kendi ayarlarınızı yapıp var ise içeriği siliyorsunuz.Yeni bir yazı yazdıktan sonra dosyaları pushlamanız yeterli.

Daha detaylı bilgi için jekyll sitesini incelemenizi öneririm.
