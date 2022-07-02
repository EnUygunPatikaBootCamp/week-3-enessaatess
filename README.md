##	Symfony kullanmanın avantajları nedir?

Symfony, PHP'nin en zengin özelliklerini barındıran frameworküdür. Modüler ve birleşenleri Symfony tercih etmemizde ki en önemli sebeplerdendir. Büyük bir community'e sahip olması hem sorunların çözümünde hemde geliştirme aşamasında büyük katkılar sunmaktadır. Ayrıca Symfony ile yüksek güvenlikli projeler hazırlayabiliriz. Birden fazla yazılımcının çalıştığı projelerde ise karışıklığı önler verimli çalışma deneyimi sunar.

##	Symfony ile environment (ortam) ayarlaması nasıl yapılır?

Teknik gereksinimlerin sağlanması gerekir. 
PHP 7.2.5 veya üzerini ve bu PHP uzantılarını (birçok PHP 7 kurulumunda varsayılan olarak kurulur ve etkinleştirilir.
PHP paketlerini kurmak için composer kurulur.
Gereksinimlerin kontrolü için `symfony check:requirements` kullanılır.

`symfony new my_project_directory --version=5.4 --webapp` ile de Symfony uygulaması oluşturulur.


## Yeni bir Symfony projesi oluşturmak için kullanılan composer komutu nedir? Alternatif bir komutla Symfony projesi oluşturabilir miyiz?

`composer create-project symfony/skeleton:"^5.4" my_project_directory` composer komutu ile projemizi oluşturabiliriz.

`symfony new my_project_directory --version=5.4 --webapp` komutu ile de kurulum yapılabilmektedir.

## Laravel framework ve Symfony framework arasındaki temel farklardan iki tanesini yazınız.

1-Symfony yeniden kullanılabilir componentler ve framework olarak konumlanırken, Laravel ise sadece framework olarak konumlanıyor.
2-Symfony , Twig kullanır. Laravel ise Blade kullanır.