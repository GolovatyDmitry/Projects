# Поиск клиентов с неоптимальными тарифами (Телеком)

**Описание проекта:** Необходимо провести мониторинг пользователей, найти тех, кто переплачивает на действующих тарифах, выделить группу пользователей с рекомендацией перейти на более выгодные для них тарифы. В ходе проекта была расчитана текущая выручка компании, определены пользователи с невыгодными для них тарифами, расчитано падение выручки при переходе всех пользователей на оптимальные тарифы, предложен вариант по снижению риска падения выручки, а также проверена статистическая гипотеза. Был создан дашборд с метриками по ТЗ.

**Данные:** Датасеты, представленные для исследования, содержат данные об использовании услуг виртуальной телефонии телеком-компании.

**Инструменты:** Pandas, Python, Seaborn, Matplotlib, применение функций, проверка статистических гипотез, Tableau.

**Выводы:** Было обнаружено 124 клиента (48% от общего количества) с неоптимальными тарифами. Было предложено перевести на оптимальные тарифы только клиентов тарифов B и C. Тем самым будет уменьшено падение выручки до 14% вместо 32% (при переводе всех клиентов) и в то же время будут улучшены тарифы для 96 клиентов (77% от количества клиентов с неоптимальными тарифами). Гипотеза о различии средней месячной выручки до и после перевода клиентов на оптимальные тарифы подтверждена (различия есть).
