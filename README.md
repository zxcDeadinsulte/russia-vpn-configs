# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45"> VPN Configs
        
Последнее обновление системы: `2026-04-11 00:00:00` (MSK)  
Всего конфигураций в базе: `20`  
Всего QR-кодов сгенерировано: `1`

---

## 📖 Введение и Терминология

Добро пожаловать в репозиторий автоматизированной сборки VPN-конфигураций EaveVPN. Данный проект создан для обеспечения свободного доступа к информации и защиты личных данных. Все конфигурации проходят автоматическое тестирование скорости и доступности перед публикацией. Обновление происходит каждые 6 часов.

Крайне важно понимать разницу между типами предоставляемых подписок, чтобы выбрать подходящий вариант для ваших нужд.

### Что такое Black List (Черный список)?

**Black List** — это режим работы VPN, при котором **весь интернет-трафик** вашего устройства направляется через удаленный сервер.

* **Назначение:** Полная анонимизация, защита в публичных Wi-Fi сетях, доступ к ресурсам, заблокированным по географическому признаку.
* **В России:** Работает как "классический" VPN. Скрывает ваш реальный IP от всех сайтов.

### Что такое White List (Белый список / Обход блокировок)?

**White List** — это специализированный режим, созданный специально для пользователей из России. В этом режиме через VPN направляется **только трафик к заблокированным ресурсам**.

* **Назначение:** **Обход блокировок Роскомнадзора** (Instagram, Facebook, Twitter, зарубежные СМИ и т.д.) без потери скорости на российских сайтах.
* **Как это работает:** Скрипт использует современный протокол (например, VLESS Reality), который маскирует VPN-трафик под обычное посещение разрешенного сайта.
* **Преимущество:** Российские сайты (VK, Mail.ru, банки, Госуслуги) открываются напрямую на максимальной скорости.

---

## 🗂 Актуальные подписки

| Имя файла | Тип | Платформа | Протоколы | Серверов | Скачать TXT | QR-код |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| **WHITE-LIST-RUS.txt** | White List | Full | `Vless` | `20` | [📥 TXT](https://raw.githubusercontent.com/zxcDeadinsulte/russia-vpn-configs/refs/heads/main/WhiteList.txt) | [🔲 QR](https://raw.githubusercontent.com/zxcDeadInsulte/russia-vpn-configs/refs/heads/main/qr-codes/White-List+1.png) |
| 
        |

---

## 🧩 Приложения для конфигов на ПК и телефоне: 

Из-за различий клиентов одни и те же конфиги могут работать по-разному. Поэтому рекомендуется иметь 2–3 клиента (например: v2rayN, Throne, Karing). Если конфиг не работает в одном — это нормально, он может заработать в другом. В среднем 70–80% конфигов запускаются в одном из клиентов.

Это же касается мобильных устройств — пробуйте разные приложения (например, на iOS: Streisand, Karing, Shadowrocket).

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> Windows/Linux/MacOS 

Установите клиент (v2rayN / Throne), запустите от администратора → вставьте конфиг (Ctrl+V) → обновите подписку → проверьте задержку (значок молнии) → отсортируйте по пингу → протестируйте скорость → выберите лучший → включите VPN/TUN режим.

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

---

### 📋 Важные замечания

* Конфигурации бесплатны и предоставляются "как есть".
* Обновляйте подписку в приложении каждые 3-4 часа.
* Формат: **TXT** (совместим с V2RayTun, Happ, Streisand, Hiddify, NekoBox и др.)
* **QR-коды**: для каждого файла конфигурации создан отдельный QR-код в папке `qr-codes/`
* Для быстрой настройки: отсканируйте QR-код камерой или приложением.

*Automated by [???](https://github.com/)*  
*Telegram: [@](https://t.me/)*
