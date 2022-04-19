## Оценка результатов А/В - тестирования

A/B-тест был проведен с целью исследования изменений, связанных с внедрением улучшенной рекомендательной системы.

Ожидается, что за 14 дней с момента регистрации в системе пользователи покажут улучшение каждой метрики не менее, чем на 10%:
- конверсии в просмотр карточек товаров;
- просмотры корзины;
- покупки.

### Цель проекта:
- провести оценку результатов A/B-теста с учетом технического задания.

В рамках проекта мною был проведен исследовательский анализ данных и оценена корректность проведения теста. Было выявлено, что тестовая аудитория пересекается с конкурирующим тестом: действия пользователей, которые одновременно участвовали в В-группе конкурирующего теста, не учитывались при анализе результатов. 

Также было проанализировано влияние маркетингового события на поведение пользователей. За время проведения Рождественской акции тестовая аудитория не начала проявлять повышенной активности в приложении, поэтому действия за время проведения акции не были исключены из анализа. 

Были построены воронки продаж для исследования конверсий и проведена оценка результатов A/B-теста. Пользователи из группы В (новая платёжная воронка) не показали улучшение конверсий, наоборот, результаты контрольной группы (А) были значительно выше. Причиной этого стало то, что многие участники из группы В не совершили ни одного действия за период тестирования. 

Из-за неравномерности пользователей, а именно малой доли фактических участников группы В, нельзя сказать, что результатам А/В-тестирования можно доверять. А/В-тест показал, что за причиной низкой конверсии скрывается проблема удержания пользователей.

**Библиотеки**, которые были использованы: Pandas, NumPy, Math, Matplotlib, Seaborn, Plotly, SciPy, Datetime, Re.