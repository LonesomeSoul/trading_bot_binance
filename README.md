# trading_bot_binance

Файлы с кодом:
trading_data - файл с кодом для импорта данных для обучения моделей.
trading_autoencoder - файлы для обучения автоэнкодера.
trading_lstm - файл для обучения модели - с использованием обученного автоэнкодера или без.
trading_backtest - файл для проверки эффективности бота на исторических данных.
trading_bot - скрипт бота. В пустой папке не будет работать, пока остальные файлы кроме trading_backtest не будут запущены хотя бы раз.

Важно:
Во всех файлах нужно указать переменную directory - путь к папке со всеми файлами. Также распаковать архив binance_files в ту же папку.
В файле trading_bot нужно указать key_api и secret_api - Это приватные данные для получения доступа к кошельку на binance.
