# Wordpress / Woocommerce Liqpay Gateway

Платёжный шлюз Liqpay для Вашего магазина на Woocommerce.

## Установка

Распакуйте архив с плагином в папку ```/wp-content/plugins``` Вашего сайта. Затем после активации плагина в админ панели он автоматически появиться в списке платёжных шлюзов Woocommerce.

## Настройка

На странице настроек шлюза необходимо вставить публичный и приватные ключи Вашего магазина, которые находяться на странице настроек магазина у Вашем личном кабинете Liqpay.

## Детали
* Опция редирект на страницу оплаты - сразу перекидыват клиента на Liqpay. Иначе - только при нажатии клиентом на кнопку LIQPAY
* Опция демо режим в плагине - деньги с клиента не снимаются. Но рекомендую демо режим включать прямо в Liqpay - тогда он даст новые ключи для теста и при оплате будет гореть ТЕСТ оплата на Liqpay
* После оплаты на странице Liqpay две ссылки - отправить чек на email (отпавляет чек, клиент остается на ткущей старнице), и вернуться в магазин (перекидывает в магазин на подробное описание заказа с "Спасибо за заказ")
* Для активации платежа - смотри требования к ИМ от Ликпкй https://github.com/nofikoff/wc-liqpay-gateway/blob/master/liqpay%5B1%5D.pdf
В частости : логотипы мастер кард и виза на сайте, номер телефона на сайте совпадает с номером телефона Liqpay, могут спросить наличие страницы "Конфиденциалность" где должно быть указано ФИО владельца магазина, совпадающего с эккаунтом Liqpay




