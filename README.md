# guild-arbitrum-swaps

Скрипт покупает все монеты, которые нужно купить в guild arbitrum чтобы получить роль. Каждый контракт вызывается отдельно, здесь вас не спалить. Количество монет покупается минимально необходимое для выполнения задания (получение роли). Суммарно с комиссиями выходит ~ 2$ в ETH.
Нужно пополнить кошелек на > 0.004 eth.

ВАЖНО! сначала скрипт покупает LPT и DBL на 1.5$ и затем сразу продает их. так и должно быть.

1. Сохраняем оба файла.
2. Вставляем в файл private_keys.txt свои ptivate key от кошельков. Кол-во >= 1. Каждый приватник с новой строки
