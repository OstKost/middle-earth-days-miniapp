# Хроники Средиземья — Telegram Mini App

Статическая страница мини‑приложения для ботов @GandalfGrayBot и @ElrondElfBot (канал @MiddleEarthDays).
Данные и действия идут через Supabase Edge Function `me-miniapp`, которая проверяет Telegram initData
(HMAC с токеном бота) и пускает только владельца. Секретов в репозитории нет.
