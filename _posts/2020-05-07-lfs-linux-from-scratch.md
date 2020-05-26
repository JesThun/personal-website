---
layout: post
published: true
title: "LFS, Linux From Scratch?"
tags: 100DaysToOffload
---

# LFS, Linux From Scratch?

[LFS](http://www.linuxfromscratch.org/lfs), Türkçeleştirilmiş adıyla **Sıfırdan Linux Yapımı**, büyük bir geliştirici topluluğu tarafından yürütülen bir projeymiş ve insanlara kendi GNU/Linux dağıtımlarını derlemelerine yardımcı olan bir [kitapları](http://www.linuxfromscratch.org/lfs/read.html) varmış. 

#### Peki ben neden bir GNU/Linux dağıtımı derlemek isteyeyim ki?

Çünkü var olan dağıtımlar benim ihtiyacımı karşılamayabilir ya da ihtiyacım olmayan paketler barındırabilir. Örneğin ben bir masaüstü ortamı kullanmak istemiyorsam sadece pencere yöneticisiyle gelen onlarca dağıtımdan birini kurmayı tercih edebilirim. Böylece kurulum diski daha düşük boyutlu olacağı gibi kurulum da daha kısa sürer. Ama bu dağıtımların içinde benim ihtiyaçlarımı karşılayacak paketlere sahip bir dağıtım olmayabilir. 
Gerçi bu tip ihtiyaçlarda Gentoo, Arch gibi dağıtımlara şans tanınabilir. Ya da Debian'ın gerçekten içi bomboş gelen netinst ISO'su tercih edilebilir.

Gelelim benim bakış açıma. Ben Linux From Scratch'i keşfettiğimde amacım Linux çekirdeğinden sonra bir dağıtımın çalışabilmesi için nelerin gerçekleştiğini merak etmemdi. Hâlâ bu amaçla yoluma devam ediyorum ve sanırım yolun yarısında bile değilim.

Bir karalamanın daha sonuna geldik. Sonrakilerde de birilerinin işine yarayacak gibi görünen ama aslında öyle olmayan içerikler olacak.


I’m publishing this as part of 100 Days To Offload. You can join in yourself by visiting [https://100daystooffload.com](https://100daystooffload.com)

Bu yazıyı 100 Days To Offload'ın bir parçası olarak yayınlıyorum. [https://100daystooffload.com](https://100daystooffload.com) adresini ziyaret ederek siz de katılabilirsiniz.

`init 0`

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
 
