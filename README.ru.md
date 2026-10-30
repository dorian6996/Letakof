<p align="center">
  <img src="assets/app-icon.png" alt="Иконка приложения Letakof" width="96" height="96">
</p>

<h1 align="center">Letakof</h1>

<p align="center">VPN- и прокси-клиент на ядре <strong>Mihomo</strong>.</p>

<p align="center">Предварительная версия для Android, macOS и Windows.</p>

<p align="center"><a href="README.md">English</a> · <strong>Русский</strong> · <a href="README.zh-CN.md">简体中文</a></p>

<p align="center">
  <a href="https://letakof.app/ru/">Сайт</a> ·
  <a href="https://letakof.app/ru/docs/">Документация</a> ·
  <a href="https://github.com/dorian6996/Letakof/releases">Релизы</a> ·
  <a href="https://github.com/dorian6996/Letakof/issues/new">Сообщить об ошибке</a>
</p>

## Возможности

- Подписки Clash/Mihomo YAML, обновление профилей и поддержка HWID. Лимит трафика, срок действия и объявления провайдера.
- Управление подписками и прокси-ключами: отдельные ключи можно добавить к подписке или использовать без неё.
- Группы прокси с проверкой задержки, автоматическим выбором сервера, резервированием и балансировкой нагрузки.
- TUN, системный прокси и локальный HTTP/SOCKS5-прокси. Доступ к прокси для устройств локальной сети по паролю.
- Сценарии сети с выбором режима работы и подписки в зависимости от типа сети на macOS и Android.
- Режим белых списков, если он включён провайдером.
- Просмотр, включение, отключение и изменение порядка правил подписки. Редактирование своих правил для доменов, IP-адресов, подсетей и портов с сохранением изменений при обновлении подписки.
- Пресеты маршрутизации, свои наборы правил и группы прокси.
- Серверы DNS по ролям, исключения fake-IP, настройки IPv6 и обновление баз GEO.
- Выбор стека TUN и управление QUIC (HTTP/3).
- Резервные копии настроек и профилей с восстановлением из файла.
- [HTTP-заголовки подписки](https://letakof.app/ru/docs/http-headers/additional-headers/) для ссылок провайдера, уведомлений о трафике и сроке действия, ограничений интерфейса.
- Просмотр соединений со сработавшими правилами, цепочками прокси и журналом ядра.
- Языки интерфейса: английский, русский, китайский (упрощённый и традиционный), вьетнамский, французский и испанский.

## Протоколы

Ядро Mihomo поддерживает VLESS, VMess, Trojan, Shadowsocks, Hysteria, Hysteria2, TUIC, WireGuard, AnyTLS, SOCKS5, HTTP и другие протоколы. Доступные серверы и параметры транспорта зависят от подписки.

Подписки используются в формате Clash/Mihomo YAML.

## Демонстрация

Подключение и раскрытие групп прокси. Профиль «Subscription», серверы с названиями стран и данные о трафике — демонстрационные.

<table>
  <tr><th>Android</th><th>macOS</th><th>Windows</th></tr>
  <tr>
    <td valign="top" align="center"><a href="assets/android-ru.gif"><img src="assets/android-ru.gif" alt="Letakof Android" width="160"></a></td>
    <td valign="top" align="center"><a href="assets/mac-ru.gif"><img src="assets/mac-ru.gif" alt="Letakof macOS" width="270"></a></td>
    <td valign="top" align="center"><a href="assets/windows-ru.gif"><img src="assets/windows-ru.gif" alt="Letakof Windows" width="270"></a></td>
  </tr>
</table>

## Релизы и баг-репорты

Сборки и описания изменений публикуются в разделе [Releases](https://github.com/dorian6996/Letakof/releases).

Баг-репорты и предложения отправляйте в [Issues](https://github.com/dorian6996/Letakof/issues). Укажите версию приложения, версию ОС и шаги воспроизведения ошибки.

<hr>

<p align="center"><sub>Letakof — проприетарное программное обеспечение. Репозиторий предназначен для релизов и баг-репортов и содержит только описание и ассеты репозитория. Исходный код приложения здесь не публикуется.</sub></p>
