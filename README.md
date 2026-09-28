# tokensView

Приложение для Windows, которое показывает, сколько токенов расходует Claude Code и сколько это стоило бы по ценам API. Интерфейс на русском и английском.

- расход по сессиям, проектам, часам, дням, неделям и месяцам с графиками, экспорт таблиц в CSV/Excel;
- стоимость по актуальным ценам Anthropic API, с учётом кэша, и сравнение: сколько стоили бы те же токены на другой модели;
- подписка Claude против цен API: выгода или переплата за расчётный период, дни до списания, прогноз;
- лимиты подписки по логам Claude Code: когда упёрлись, когда снимется, оценка лимита и прогноз следующего упора;
- активность: время ответов Claude, ваши паузы, активная работа по часам и тепловая карта по дням недели;
- бюджеты и уведомления Windows (лимит достигнут/снят, бюджет превышен);
- значок в трее, запуск вместе с Windows и компактный виджет поверх окон с графиком токенов по проектам.

## Установка

Скачайте `tokensView-Setup-*.exe` из последнего релиза в разделе [Releases](https://github.com/YANGROK-lab/tokensView-releases/releases/latest) и запустите его. Дальше программа обновляется сама.

Программа не подписана сертификатом, поэтому при первом запуске Windows может показать «Windows защитила ваш компьютер». Нажмите **Подробнее → Выполнить в любом случае**.

## Подписка

Программа работает только по подписке — **$1 в месяц**. Бесплатного и пробного периода нет.

1. Установите программу. На первом экране будет **код этого компьютера** — скопируйте его.
2. Напишите в Telegram [@fpacchub](https://t.me/fpacchub), оплатите подписку и отправьте код.
3. Вставьте полученный ключ на том же экране.

Ключ работает только на компьютере, для которого выдан. После переустановки Windows код компьютера меняется, и понадобится новый ключ — напишите в тот же Telegram.

## Приватность

Программа читает только локальные логи Claude Code (`%USERPROFILE%\.claude\projects`) и никуда их не отправляет. В интернет она обращается только за обновлениями на GitHub.

---

## English

tokensView shows how many tokens Claude Code uses and what that would cost at Anthropic API prices: sessions, projects, periods, your Claude plan vs API prices, usage limits, activity, budgets and notifications, a tray icon and an always-on-top widget.

**Install:** download `tokensView-Setup-*.exe` from the [latest release](https://github.com/YANGROK-lab/tokensView-releases/releases/latest) and run it; it updates itself. The app is not code-signed, so Windows may say "Windows protected your PC" — click **More info → Run anyway**.

**Subscription:** $1 per month, no free trial. Copy the computer code from the first screen, message [@fpacchub](https://t.me/fpacchub) on Telegram, pay and send the code; paste the key you receive. A key works on that computer only.

**Privacy:** the app reads only the local Claude Code logs and sends nothing anywhere; it goes online only to check GitHub for updates.
