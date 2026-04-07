# Анализ результатов A/B теста дейтингового приложения

## Описание проекта
Проект выполнен в рамках курса по анализу данных. Цель – оценить успешность A/B-теста, проведённого в крупном дейтинговом приложении. В тесте для новых пользователей из нескольких стран изменялась стоимость премиум-подписки при покупке через две новые платёжные системы. Пробный период оставался прежним. Необходимо проверить, был ли эксперимент успешен.

## Стек
<p>
  <img width="98" height="28" alt="image" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img width="110" height="28" alt="image" src="https://img.shields.io/badge/datetime-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

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


