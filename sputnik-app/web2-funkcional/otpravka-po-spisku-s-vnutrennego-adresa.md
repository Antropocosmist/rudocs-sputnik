---
description: >-
  "Сигналы спутника имели вид телеграфных посылок («бипов») длительностью около
  0,4 секунды и с такой же длительностью пауз"
---

# Отправка по списку с Внутреннего Адреса

В [**Личном Кабинете**](../lichnyi-kabinet.md), Пользователь может отправить токены или NFT с [**Внутреннего Адреса**](../../slovar-terminov-i-skhema/vnutrennii-adres.md) по списку, который состоит из блокчейн-адресов, юзернеймов, или электронных почт

Для этого:

* Пользователь должен выбрать "Мульти Отправка" в меню [**Личного Кабинета**](../lichnyi-kabinet.md)
* В качестве отправителя выбрать свой [**Внутренний Адрес**](../../slovar-terminov-i-skhema/vnutrennii-adres.md)
* В качесте получателей указать список из блокчейн-адрес, либо Telegram, Twitter, Discord юзернеймов, либо электронных почт
* Указать количество и тип токенов
* Нажать на кнопку "Отправить"

Для всех получателей на блокчейн-адреса, [**Sputnik App**](../../sputnik-network-app-chain/sputnik-dapp.md) совершит мульти-сенд транзакцию с [**Внутреннего Адреса**](../../slovar-terminov-i-skhema/vnutrennii-adres.md) на блокчейн-адреса

Для всех получателей по юзернеймам и/или электронным адресам, [**Sputnik App**](../../sputnik-network-app-chain/sputnik-dapp.md) обратится к [**Внутренней Записии**](../../slovar-terminov-i-skhema/vnutrennyaya-zapis.md), и:

* Для всех юзернеймов и электронных почт, о которых во [**Внутренней Записии**](../../slovar-terminov-i-skhema/vnutrennyaya-zapis.md) есть информация об ассоциации юзернеймов или электронных почт с блокчейн-дресами - [**Sputnik App**](../../sputnik-network-app-chain/sputnik-dapp.md) совершит мульти-сенд транзакцию с [**Внутреннего Адреса**](../../slovar-terminov-i-skhema/vnutrennii-adres.md) на блокчейн-адреса
* Для всех юзернеймов и электронных почт, о которых во [**Внутренней Записии**](../../slovar-terminov-i-skhema/vnutrennyaya-zapis.md) нет информация об ассоциации юзернеймов или электронных почт с блокчейн-дресами - [**Sputnik App**](../../sputnik-network-app-chain/sputnik-dapp.md) совершит транзакцию на [**Адрес Приложения**](../../slovar-terminov-i-skhema/adres-prilozheniya.md), и внесёт во [**Внутреннюю Запись**](../../slovar-terminov-i-skhema/vnutrennyaya-zapis.md) информацию о том, что данные токены или NFT должны быть отправлены на [**Внутреннии Адреса**](../../slovar-terminov-i-skhema/vnutrennii-adres.md) пользователей, которые прикрепят указаные юзернеймы или электроннуе почты в [**Личном Кабинете**](../../slovar-terminov-i-skhema/lichnyi-kabinet.md)
* Если в течение года никто не прикрепит эти юзернеймы или электронные почты к [**Личному Кабинету**](../lichnyi-kabinet.md) - [**Sputnik App**](../) отправит эти токены или NFT с [**Адреса Приложения**](../../slovar-terminov-i-skhema/adres-prilozheniya.md) в **Пул Сообщества** [**Sputnik Network App-chain**](../../sputnik-network-app-chain/)

Отправка токенов или NFT с [**Личного Адреса**](../../slovar-terminov-i-skhema/lichnyi-adres.md) по списку состоящему из блокчейн-адресов, юзернеймов и/или электронных почт - относится к [**Web3 функционалу**](../web3-funkcional/), и [**Sputnik App**](../../sputnik-network-app-chain/sputnik-dapp.md) не имеет доступа к токенам или NFT на [**Личном Адреса**](../../slovar-terminov-i-skhema/lichnyi-adres.md) пользователя, даже если [**Пользователь**](../../slovar-terminov-i-skhema/polzovatel.md) прикрепил [**Личный Адрес**](../../slovar-terminov-i-skhema/lichnyi-adres.md)
