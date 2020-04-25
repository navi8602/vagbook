---
layout: docs
title: Активация Hill Hold Assistant (Помощ при спуске с горы)
weight: "16"
description: Активация Hill Hold Assistant (Помощ при спуске с горы)
keywords: Активация Hill Hold Assistant (Помощ при спуске с горы)
date: 2020-04-19T12:12:46.784Z
---
## Активация Hill Hold Assistant (Помощ при спуске с горы)

{{< hint info >}}В блоке управления тормозами и ABS вы можете активировать функцию Hill Hold Assistant (Hill Start Assist) на Audi A3 8P / 8PA{{< /hint >}}

{{< hint warning >}}  
**Доступно на моделях:**\
**Модель:** Audi A3 8P / 8PA\
**Год выпуска:** 2011\
**Модельный год:** MJ11
{{< /hint>}}

### **Кодирование блока 7 (Тормоза | ABS )**

1. Выберете блок 7 (Тормоза | ABS )
2. Длинное кодирование
3. Выберете байт 16 и поставить галочку в бит 0
4. Адаптация
5. Выберете канал "Hill start assist"
6. Установите нужное значение:\
   0 = Hill start assist "normal"\
   1 = Hill start assist "early" (старт на низкой скорости)\
   2 = Hill start assist "late" ((запуск с более высокой скоростью и скользящая муфта)


{{< hint danger >}}И помните, что все манипуляции с блоками и кодировкой, Вы делаете на свой страх и риск.{{< /hint>}}