# Написать смарт-контракт вида "кошелек".

Смарт-контракт должен иметь необходимую и достаточную функциональность, чтобы контракт мог использоваться в качестве обычного адреса в сети Ethereum:

- Возможность отправлять/принимать ETH
- Возможность отправлять/принимать токены
- Возможность делать allowance для токенов

В смарт-контракте должен присутствовать метод или функциональность, который позволяет установить комиссию для переводов эфира:

- Должен присутствовать метод, изменяющий значение этой комиссии
- Комиссия - представляет из себя какое-то число от переводимой суммы
- Перевод этой комиссии должен производиться вместе с обычным переводом
- Адрес для перевода зашит в контракт хардкодом
