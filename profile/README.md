# Mooncore-inc

Demon Cry - open-source экосистема для автоматизации OSINT-исследований и работы с LLM-агентами. 
Архитектура построена по принципу ядра и подключаемых модулей через entry points.

## 🏗 Архитектура экосистемы

### Ядро и инструменты разработки
Эти репозитории являются фундаментом системы.

| Репозиторий | Описание |
| :--- | :--- |
| [**demon-cry**](https://github.com/Mooncore-inc/demon-cry) | Основное ядро, оркестратор. |
| [**demon-cry-python-sdk**](https://github.com/Mooncore-inc/demon-cry-python-sdk) | Python SDK для интеграции агента в сторонние приложения. |
| [**demon-cry-base**](https://github.com/Mooncore-inc/demon-cry-base) | Базовый класс для создания OSINT-модулей. |

### Официальные модули
Независимые пакеты, расширяющие функциональность ядра. Устанавливаются отдельно через pip.

| Модуль | Назначение |
| :--- | :--- |
| [**dc-dns**](https://github.com/Mooncore-inc/dc-dns) | Асинхронный резолвинг DNS-записей (A, AAAA, MX, TXT и др.). |
| [**dc-whois**](https://github.com/Mooncore-inc/dc-whois) | Получение и парсинг данных регистрации доменов через RDAP/WHOIS. |
| [**dc-web-search**](https://github.com/Mooncore-inc/dc-web-search) | Модуль веб-поиска на базе SearXNG. |
| [**dc-parse-website**](https://github.com/Mooncore-inc/dc-parse-website) | Модуль парсинга содержимого веб-страниц. |


## 🤝 Участие в разработке

Мы приветствуем создание сторонних модулей. 

---
*Разрабатывается и поддерживается сообществом Mooncore-inc.*