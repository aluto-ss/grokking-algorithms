# Задача о просмотре достопримечательностей

## Условие

Представьте, что вы приехали в Лондон на выходные. У вас два дня, а мест, которые хочется посетить, слишком много. Побывать везде не получится, поэтому вы составляете список.

Достопримечательность|Время|Оценка
-|-|-
Вестминстерское аббатство|0.5 дня|7
Театр Глобус|0.5 дня|6
Национальная галерея|1 день|9
Британский музей|2 дня|9
Собор святого Павла|0.5 дня|8

[Заполнение таблицы](./able.md)

***
***

Код:

```
const places = [
  {
    name: "Westminster Abbey",
    price: 7,
    size: 0.5
  },{
    name: "Globus Theatre",
    price: 6,
    size: 0.5
  },{
    name: "National Gallery",
    price: 9,
    size: 1
  },{
    name: "British Museum",
    price: 9,
    size: 2
  },{
    name: "St Paul's Cathedral",
    price: 8,
    size: 0.5
  }
]

knapsack(places, 2); // 24, Westminster Abbey + National Gallery + St Paul's Cathedral

```

Команда для проверки:

```
npm run knapsack-places
```

***
***