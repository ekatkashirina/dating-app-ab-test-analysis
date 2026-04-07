# Анализ результатов A/B теста дейтингового приложения

## Описание проекта
Проект выполнен в рамках курса по анализу данных. Цель – оценить успешность A/B-теста, проведённого в крупном дейтинговом приложении. В тесте для новых пользователей из нескольких стран изменялась стоимость премиум-подписки при покупке через две новые платёжные системы. Пробный период оставался прежним. Необходимо проверить, был ли эксперимент успешен.

## Стек
<div>
  <img src="https://img.shields.io/badge/python-white?logo=python&style=for-the-badge" title="Python" alt="Python" height="40"/>&nbsp;
  <img src="https://img.shields.io/badge/datetime-white?logo=python&logoColor=blue&style=for-the-badge" title="datetime" alt="datetime" height="40"/>&nbsp;
  <img src="https://img.shields.io/badge/pandas-white?logo=pandas&logoColor=blue&style=for-the-badge" title="Pandas" alt="Pandas" height="40"/>&nbsp;
  <img src="https://img.shields.io/badge/numpy-white?logo=numpy&logoColor=black&style=for-the-badge" title="NumPy" alt="NumPy" height="40"/>&nbsp;
  <img src="https://img.shields.io/badge/scipy-white?logo=scipy&logoColor=black&style=for-the-badge" title="SciPy" alt="SciPy" height="40"/>&nbsp;
  <img src="https://img.shields.io/badge/matplotlib-white?logo=matplotlib&logoColor=black&style=for-the-badge" title="Matplotlib" alt="Matplotlib" height="40"/>&nbsp;
  <img src="https://img.shields.io/badge/seaborn-white?logo=seaborn&logoColor=black&style=for-the-badge" title="Seaborn" alt="Seaborn" height="40"/>&nbsp;
  <img src="https://img.shields.io/badge/jupiter-white?logo=jupyter&logoColor=orange&style=for-the-badge" title="Jupiter" alt="Jupiter" height="40"/>&nbsp;
</div>

## Данные
- Источник: данные предоставлены в рамках курса.
- Содержание: информация о пользователях и их транзакциях по группам: тестовая, контрольная группа 1 и контрольная группа 2.
- Особенности: пропуски, дубликаты, некорректные типы данных, некорректная выгрузка логов с датами.

## Задачи
1. Предобработка и очистка данных.
2. A/A тест в контрольных группах.
3. Выдвижение гипотезы для A/B-тестирования и выбор метрик для оценки результатов.
4. Расчёт метрик в группах.
5. Оценка результатов A/B-тестирования. Анализ статистической значимости различий с использованием t-критерия, z-теста, bootstrap, хи-квадрат, теста Левена, теста пропорций.
6. Формулирование выводов и предложений.


