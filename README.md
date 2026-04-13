> [!CAUTION]
> В данном скрипте используется сборка MTProto от [9seconds](https://github.com/9seconds/mtg).
> 
> По моим личным наблюдениям, несмотря на [недавний фикс](https://github.com/9seconds/mtg/pull/446) FakeTLS ServerHello, эта сборка работает менее стабильно, чем [Telemt](https://github.com/telemt/telemt).
>
> Сам я сейчас полностью перешел на Telemt, в соседней репе лежит [текстовый мануал](https://github.com/skarusto/telemt-manual) по настройке Telemt + Caddy + RST block. Рекомендую использовать её.
>
> Данный скрипт больше обновлять не планирую.

# GoTelegram: MTProto с fake TLS

**Автор оригинального скрипта:** https://github.com/anten-ka

**Оригинальный репозиторий:** https://github.com/anten-ka/gotelegram_mtproxy

## Изменения
**Удалено:** реклама, промо, реферальные ссылки

**Добавлено:** возможность ввода кастомного домена для маскировки

---

## Быстрая установка

Скопировать команду и запустить в терминале сервера (работает на Ubuntu/Debian/CentOS):

```bash
wget -O setup_gotelegram.sh https://raw.githubusercontent.com/skarusto/gotelegram_mtproxy/main/setup_gotelegram.sh && chmod +x setup_gotelegram.sh && sudo ./setup_gotelegram.sh
```

## Управление
Команда **gotelegram** в консоли
