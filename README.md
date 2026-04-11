# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45"> VPN Configs
        
Последнее обновление системы: `2026-04-11 00:00:00` (MSK)  
Всего конфигураций в базе: `20`  
Всего QR-кодов сгенерировано: `1`

---



---

## 🧩 Приложения для конфигов на ПК и телефоне: 

В зависимости от клиента могут отличаться рабочие сервера. Поэтому поставьте себе на ПК 2-3 разных клиента: v2rayN, Throne и Karing. Например, в v2RayN конфиги могут все пропинговаться идеально, но часть может не "завестись" по скорости - но это НЕ значит, что они "плохие" (уточню, что конфиги на момент обновления - почти все рабочие), просто v2rayN не смог их правильно "завести", это нормально из-за особенностей работы каждого клиента в отдельности. Часть не работающих полноценно конфигов в v2RayN отлично заработает в Throne, часть - в Karing и других клиентах, поэтому подбирайте что вам ближе и удобнее. Конфигов в целом много, поэтому, даже если часть не заводится - не беда, 70-80% заработает через один клиент уж точно.

Эта особенность касается и клиентов на мобильных устройствах. Например, на iOS, кроме Streisand можно поставить Karing или Shadowrocket и сравнить.

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> Windows/Linux/MacOS 

Установите официальный клиент v2rayN или Throne (преемник Nekoray), запустите в "режиме Администратора", добавьте конфиг/подписку через Ctrl+V, загрузите подписку через "Группа подписки" - "Обновить текущую подписку без прокси", появится список, нажмите на проверку "Реальной задержки" (значок молнии сверху справа), после завершения - отсортируйте по пингу, выберите несколько верхних зеленых конфигов с наименьшим числом, нажмите правую клавишу мышки - выберите "Тест на скорость загрузки сервера", после теста выберите самый быстрый, нажав на нем Enter, в конце запустите "Режим VPN/Режим TUN".

**1)** **v2rayN:**
  
   *Рекомендую v2rayN, т.к. стабильно и проверено работает с тысячами конфигов разных протоколов за раз (мой личный максимум 150.000 конфигов). Это самый универсальный клиент из всех. Идеален для массовых проверок. Работает, используя Xray, Sing-Box, Mihomo в одной связке.*

   https://github.com/2dust/v2rayN/releases
  
   `v2rayN-windows-64.zip` для Windows
  
   `v2rayN-linux-64.deb` для Linux (Ubuntu)
  
   `v2rayN-macos-64.dmg` для MacOS

**2)** **Throne (преемник заброшенного Nekoray, Nekoray не обновляют с 2024 года)**:

*Рекомендую как альтернативный рабочий клиент после v2rayN. Конфигурации, которые "не завелись" в v2rayN - частично заводятся здесь. Подходит для массовых проверок.*

   https://github.com/throneproj/Throne/releases

   `Throne-1.0.8-windows64-installer.exe` для Windows
  
   `Throne-1.0.8-debian-x64.deb` для Linux (Ubuntu)
  
   `Throne-1.0.8-macos-arm64.zip` для MacOS

**3)** **Karing:**

*Рекомендую как еще один альтернативный клиент после v2rayN. Конфигурации, которые "не завелись" в v2rayN - частично заводятся здесь. Не подходит для массовых проверок.*

   https://github.com/KaringX/karing/releases

   `karing_1.2.10.1300_windows_x64.exe` для Windows
  
   `karing_1.2.10.1300_linux_amd64.deb` для Linux (Ubuntu)
  
   `karing_1.2.10.1300_macos_universal.dmg` для MacOS
   
**4)** **Singbox-launcher:** 

  *Новый достойный внимания клиент для тестирования VPN-конфигураций, работает в связке с Sing-Box. Пробуйте, разработчик приветлив и всегда на связи.*

   https://github.com/Leadaxe/singbox-launcher/releases

   `singbox-launcher-v0.7.1-win64.zip` для Windows
  
   `singbox-launcher-v0.7.1-macos.zip` для MacOS

### <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3aGcxcG8yMGNzOTNmZDE1Z3hob3V3ajU4dmhkdnhsY2doMXFrNXowMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/oFSDc1Oq12Ie5NJnmA/giphy.gif" width="20"> iOS - используйте Streisand, Shadowrocket, Karing, V2Box или v2RayTun из App Store.

  Рекомендую Streisand, так как заявлено об отсутствии сбора данных в App Store, а также все функции, включая смену DNS работают исправно в отличие от других подобных клиентов, загрузка и работа конфигов стабильна.

  Happ не рекомендуется пользователями из-за нестабильной работы/пинга.

   **1)** `Streisand` https://apps.apple.com/us/app/streisand/id6450534064 
   
   *Лучший бесплатный клиент для iOS без сбора данных*

   **2)** `Shadowrocket` https://apps.apple.com/us/app/shadowrocket/id932747118 
   
   *Не теряет соединения даже после долгого ожидания, не ведется сбор данных, но платный*

   **3)** `Karing` https://apps.apple.com/us/app/karing/id6472431552
     
   *Хорошая альтернатива Streisand*

   **4)** `V2Box` https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690

   **5)** `v2RayTun` https://apps.apple.com/us/app/v2raytun/id6476628951
  
### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20"> Android - используйте v2rayNG и NekoBox из GitHub или v2Box и v2RayTun из Google Play.

 Рекомендую v2rayNG, так как это аналог моего фаворита v2rayN для ПК от того же разработчика "2dust", но для Андроида.

 Также попробуйте NekoBox, пользователи хвалят.

 Happ не рекомендуется пользователями из-за нестабильной работы/пинга.

  **1)** `NekoBox` https://github.com/MatsuriDayo/NekoBoxForAndroid/releases

  **2)** `v2rayNG`  https://github.com/2dust/v2rayNG/releases

  **3)** `v2Box` https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box

  **4)** `v2RayTun` https://play.google.com/store/apps/details?id=com.v2raytun.android&hl=en&pli=1

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Z25rOXRoeW1xODR1dWh2b3UycTd6YnB0Y2hlMTZtaDluZW1uNnl4ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/CeYEKonyFQyzWhxmvd/giphy.gif" width="40"> ДИСКЛЕЙМЕР

> *Автор не является владельцем/разработчиком/поставщиком перечисленных VPN-конфигураций. Это независимый информационный обзор и результаты тестирования.*
>
> *Данный пост не является рекламой VPN. Весь материал предназначен исключительно в информационных целях, и только для граждан тех стран, где эта информация легальна, как минимум - в научных целях. Если вам такое читать нельзя - закройте эту страницу немедленно!* 
>
> *Автор не имеет никаких намерений, не побуждает, не поощряет и не оправдывает использование VPN и любых других программ ни при каких обстоятельствах.*
>
> *Ответственность за любое применение данных VPN-конфигураций — на их пользователе.*
>
> *Отказ от ответственности: автор не несёт ответственность за действия третьих лиц и не поощряет противоправное использование VPN.*
>
> *Автор не несет ответственности за точность, полноту и достоверность опубликованных данных. Все совпадения случайны. Вся информация предоставлена «как есть» и может не соответствовать действительности.*
>
> *Используйте в соответствии с местным законодательством.* 
>
> *Используйте VPN только в законных целях: в частности - для обеспечения вашей безопасности в сети и защищённого удалённого доступа, и ни в коем случае не применяйте данную технологию для обхода блокировок.*
>
> *Проект некоммерческий, бесплатный, вся представленная "платежная" информация найдена случайным образом где-то в интернет-пространстве, скопирована "как есть" для демонстрации возможного примера и автору не принадлежит.*
