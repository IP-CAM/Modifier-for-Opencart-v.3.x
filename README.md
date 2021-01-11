# Наборы модификаторов для Opencart
Все модификаторы проверялись на Opencart 3.x. Работа в других версиях не гарантируется.

### Список модификаторов:
- [remove_required_email](#remove_required_email)
- [add_utm_to_retailcrm](#add_utm_to_retailcrm)

___
#### remove_required_email
Делает поле **email** необязательным для заполнения и отключает отправку письма покупателю если это поле не заполнено.

---
#### add_utm_to_retailcrm
Сохраняет UTM метки в куки, сохраняет их в переменную **utm_params** для использования в письме администратору и передает их в retailCRM (необходима установка [модуля retailCRM](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=26049)).