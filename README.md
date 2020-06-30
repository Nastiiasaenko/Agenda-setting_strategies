# Введение  
Краткое описание работы и основные результаты можно посмотреть в этой [презентации](https://drive.google.com/file/d/19g0yzj_QnY03k6_-aXdXh88I50c5HTn0/view?usp=sharing).

Основная практическая цель проекта - с помощью методов тематического моделирования и машинного обучения определить тематическое содержание новостных повесток. 

# Ход работы  
### Данные 

Данные для исследования были собраны  в ручную с помощью API VK и публичного API New York Times. Также был использован готовый [датасет](https://www.kaggle.com/snapcrack/all-the-news) по американским новостям  c сайта [kaggle](kaggle.com).
В итоговую выборку попали 5 российских новостных изданий ( всего 567307 новостей для классификации) и около 15 американских новостных изданий( всего 674654 новостей). 

### Предобработка текстовых данных 

Первый шаг - предобработка текстов( лемматизация, нормализация, токенизация). Пример preprocessing функции можно найти в файле preprocessor .ipynb



