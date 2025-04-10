# Статистический анализ данных

## Условие задания

### 1. Выборка данных
- Найти выборку данных объемом **n >= 40** для любого количественного показателя.
- Источники данных: Белстат, Национальный банк, Всемирный банк и другие.
- Данные должны быть **пространственными**. Если данные представлены в виде временного ряда, необходимо уточнить возможность их использования (например, курсы валют использовать нельзя).

---

### 2. Статистический анализ данных

#### Основные шаги:
1. **Расчет базовых характеристик**:
   - Мода, медиана, среднее значение, дисперсия, коэффициент вариации.
2. **Оценка однородности выборки**:
   - Использовать коэффициент вариации для оценки однородности.
3. **Обработка выбросов**:
   - Удалить выбросы, если они есть (сравнение с медианой).
4. **Разбиение на интервалы**:
   - Количество интервалов рассчитывается по формуле:
     - `s = 1 + [log2n]` или `s = 1 + [3,322 * lg n]`.
5. **Графическое представление**:
   - Построить полигон и гистограмму. На основе их вида сделать предположение о виде распределения выборки.
6. **Числовые характеристики**:
   - Рассчитать среднее значение, дисперсию и стандартное квадратическое отклонение.
7. **Групповые дисперсии**:
   - Рассчитать групповые дисперсии, внутригрупповую дисперсию, межгрупповую дисперсию. Проверить правило сложения дисперсий.
8. **Дополнительное разбиение**:
   - Разбить выборку на `s-1` и `s+1` интервалов. Рассчитать дисперсии и оценить, какое разбиение лучше (на основе доли межгрупповой дисперсии в общей).

---

### 3. Проверка соответствия закону распределения
- Проверить соответствие выборки предполагаемому закону распределения (используя критерии Пирсона, Колмогорова и другие).

---
