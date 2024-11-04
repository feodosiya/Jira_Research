# Jira_Research
Каждый активный проект в Jira генерирует большое количество данных, в том числе текстовых: задачи, сроки, комментарии, статусы, время выполнения, логи. Часть объектов - пользовательские. При правильном анализе таких данных можно выявить зоны повышенного риска и вовремя скорректировать процесс разработки и value stream. 

Информация о текущей загрузке разработчиков и уже запрошенных доработках в открытых репозиториях доступна онлайн, как и опция создания собственных feature requests. Благодаря такой схеме взаимодействия у нас появляется материал для изучения пользовательских потребностей в вопросах доработок ПО и порядка их рассмотрения.

В качестве основы для исследования использую данные, собранные из 16 открытых на период 2021-2022 гг репозиториев (Apache, Jira, MongoDB и проч.) и включающие 1822 проекта, ~2.7 млн задач с учетом 32 млн изменений, 9 млн комментариев, 1 млн связей.

## Датасет
Описание датасета: [An Alternative Issue Tracking Dataset of Public Jira Repositories](https://arxiv.org/pdf/2201.08368)
Датасет скачан с открытой платформы [Zenodo](https://zenodo.org/records/7182101) и загружен в локальную MongoDB.
