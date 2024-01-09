## Özet

Laravel 10 ile yeni bir rest api projesine başlanacağı zaman laravel passport kütüphanesinin kullanıldığı, kullanıcı yetkilendirme özelliğinin olduğu temel bir laravel projesidir.



# Kurulum

* Projeyi indirin ve dizine çıkarın.

* Dizindeyken composer ile bağımlılıkları yükleyin.

`composer update`

* Mysql de bir veritabanı oluşturun. 

* `.env.example` dosyasının `.env` olarak değiştirin.

* .env dosyasında veritabanı `(DB)` ayarlarınızı yapın.

* Aşağıdaki artisan komutu ile tabloları oluşturun

`php artisan migrate`

###### Projeyi çalıştırmak 

`php artisan serve`

###### Kullanılabilir route lar

* POST `api/register`
* POST `api/login`
* GET `api/profile`
* GET `api/logout`

