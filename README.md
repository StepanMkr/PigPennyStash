# PigPennyStash - Приложение для учета финансов

## 1. Общие сведения
- **Название проекта**: PigPennyStash (кодовое название)
- **Тип приложения**: 
  - Мобильное (iOS/Android - приоритет)
  - Web-версия (опционально)
- **Основная цель**: Учет личных/совместных финансов, контроль расходов/доходов и накоплений
- **Особенности**:
  - Независимость от конкретных банков
  - Поддержка мультивалютности
  - Совместные счета и цели

## 2. Функциональные требования

### 2.1. Управление счетами
- Создание неограниченного количества счетов (ручной ввод/импорт)
- Типы счетов:
  - Личные (только владелец)
  - Совместные (доступ у нескольких пользователей)
- Возможность добавить категории кешбека на карте, чтобы удобно контролировать и использовать свои бонусы.

### 2.2. Транзакции
- Ручное добавление доходов/расходов
- История транзакций с фильтрами:
  - По дате, категориям, счетам, статусам (завершено/ожидание)
- Опционально: автоматическое добавление транзакций

### 2.3. Цели и накопления
- Создание целей (например, "Накопить на отпуск – 100 000 ₽")
- Фичи:
  - Фиксированный процент от дохода автоматически зачисляется в цель.
  - Кастомные категории целей ("Ремонт", "Подарок")
  - Опционально: совместные цели с вкладом нескольких пользователей

### 2.4. Категории доходов/расходов
- Стандартные категории (еда, транспорт, развлечения)
- Создание своих категорий/подкатегорий
- Аналитика по доходам/расходам
- Учет постоянных расходов

### 2.5. Аналитика и отчеты
- Графики и диаграммы:
  - Круговые (по категориям)
  - Линейные (динамика за период)

### 2.6. Уведомления
- О регулярных платежах (ЖКХ, подписки)
- О достижении целей
- О добавлении вас в контрибьюторы события одним из ваших контактов
- О крупных расходах (при превышении лимита)

### 2.7. Социальные функции
- Список "друзей" (другие пользователи)
- Совместные счета и события
- Опционально: синхронизация с контактами телефона

### 2.8. Мультивалютность
- Поддержка любых валют
- Выбор валюты в настройках
- Автоматический пересчет по курсу ЦБ/другому источнику

### 2.9. Создание события
- Добавление событий с параметрами:
  - Название
  - Общая сумма и личный вклад (сумма, которая при наличия сразу же будет вычитаться из общего банка)
  - Распределение суммы (ручное/по %/по долям)
  - Дедлайн
  - Автозакрытие при полной оплате всеми
- Редактирование события после создания
- Добавление контрибьюторов из контактов
- Уведомление об ошибочном добавлении
- Опционально: визуальное разделение оплативших/неоплативших

### 2.10. Настройки
- Выбор валюты
- Выход из профиля
- Опционально: смена темы
- Смена пароля

### 2.11. Регистрация/вход
- Регистрация по email
- Привязка телефона (для контактов и входа)
- Опционально:
  - Вход по коду (без пароля)
  - Вход через Google/Яндекс (не рекомендуется)
