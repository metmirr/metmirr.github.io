---
layout: post
author: metin
categories: Virtualenv
---

Virtualenv ile normal olarak oluşturulan bir oram başka bir yere taşındığında çalışmayacaktır. Bunun için `--relocatable` seçeneği kullanılmalıdır.

Ancak bazı sorunlar çözülmemekle beraber hala devam etmektedir. Bunun için tavsiye edilen projeniz için belli bir yerde karar vermeniz ve orada geliştirme süresince kalmanızdır.

Daha önce oluşturduğunuz bir ortama taşınabilir özelliği kazandırmak için:

    $ virtualenv --relocatable myvenv

komutu ile ortamınız taşınabilir olacaktır.
