# Исследование надежности заемщиков

### Описание проекта
По статистике, предоставленной кредитным отделом банка, о платежеспособности клиентов нужно определить, 
влияет ли семейное положение и количество детей на погашение кредита в срок. 
 
Заказчик (кредитный отдел банка) планирует использовать результаты исследования при построении модели кредитного 
скоринга - специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

**Вывод:**

С большей вероятностью кредит банку отдаст вовремя заемщик состоящий в браке, без детей, с доходом 250 000 - 500 000, 
который хочет приобрести недвижимость.

### Использованные библиотеки

```
pandas
pymystem3
Counter (from collections)
```
### Описание данных

  - children — количество детей в семье
  - days_employed — трудовой стаж в днях
  - dob_days — возраст клиента в годах
  - education — образование клиента
  - education_id — идентификатор образования
  - family_status — семейное положение
  - family_status_id — идентификатор семейного положения
  - gender — пол клиента
  - income_type — тип занятости
  - debt — имел ли задолженность по возврату кредитов
  - total_income — доход в месяц
  - purpose — цель получения кредита

