# Игры — Формирование модели монетизации

## Описание проекта:

Была выполнена **основная задача проекта** - сформировать модель монетизации игрового приложения.

В ходе исследования была предложена модификация базовой модели, предоставленной заказчиком. Предоставлены рекомендации после внедрения новой модели повторно провести эксперимент. Был проведен анализ рекламных источников, в ходе которых были выявлены наиболее интересные и прибыльные источники для проведения рекламы. 
 


## Данные:

Датасет game_actions.csv:
- время события;
- одно из трёх событий:
- объект построен,
- первый уровень завершён,
- проект завершён;
- один из трёх типов здания:
- сборочный цех,
- космопорт,
- исследовательский центр;
- идентификатор пользователя;
- тип реализованного проекта;
Помимо основного датасета есть два датасета с информацией о рекламных активностях. Они также помогут в решении задачи.

Датасет ad_costs.csv содержит колонки:

- день, в который был совершен клик по объявлению;
- источник трафика;
- cтоимость кликов.

Датасет user_source.csv содержит колонки:

- идентификатор пользователя;
- источников, с которого пришёл пользователь, установивший приложение.

## Библиотеки:

`pandas`, `numpy`, `datetime`, `timedelta`, `matplotlib`, `pyplot`, `seaborn`, `scipy.stats`, `math`
