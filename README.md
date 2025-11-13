# 🌐 API Тестирование: REST & SOAP

## 📋 О проекте
Тестирование API веб-сервисов с использованием Postman. Включает REST API интернет-магазина и SOAP API сервиса стран.

## 🎯 Цели проекта
- Освоение тестирования REST API через Swagger документацию
- Практика работы с SOAP Web Services
- Создание автотестов с использованием AI-инструментов
- Развитие навыков тестирования API

## 🛠️ Технологии и инструменты
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![SOAP](https://img.shields.io/badge/SOAP-8A2BE2?style=for-the-badge)
![DeepSeek](https://img.shields.io/badge/DeepSeek-0066CC?style=for-the-badge)

## 📊 Результаты API тестирования


### REST API (Интернет-магазин):
- ✅ **5 эндпоинтов** протестировано
- 🛍️ **Products:** Полный CRUD цикл (GET, POST, PUT, DELETE)
- 🔍 **Покрытие:** 100% методов Products из Swagger документации

### SOAP API (CountryInfoService):
- ✅ **4 операции** протестировано
- 🌍 **Coverage:** ListOfCountryNamesByName, CapitalCity, CountryIntPhoneCode, FullCountryInfo

### Автотесты для Products:
- ✅ **10+ автотестов** создано через DeepSeek
- ✅ **Проверки:** статус-коды (200, 201, 400, 404), валидация JSON схемы, время ответа
- ✅ **Негативное тестирование:** невалидные ID, отсутствующие товары

## 🔄 Процесс тестирования

### 1. Анализ документации
- [📖 Swagger документация](https://intern.demoshopping.ru/api-docs/)
- [📋 WSDL CountryInfoService](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL)

### 2. Создание коллекций
- [📡 REST коллекция](https://www.postman.com/mrfint74-8307056/workspace/vitaly-kazarinov-s-workspace/folder/49388935-50857ba0-c192-4bd0-8242-323361c4a2ca?action=share&creator=49388935&ctx=documentation) для интернет магазина
- [🔄 SOAP коллекция](https://www.postman.com/mrfint74-8307056/workspace/vitaly-kazarinov-s-workspace/folder/49388935-50857ba0-c192-4bd0-8242-323361c4a2ca?action=share&creator=49388935&ctx=documentation) - операции стран

### 3. Автотестирование
- 🤖 Генерация тестов через DeepSeek
- ✅ Проверка статус-кодов (200, 400, 401, 404)
- ✅ Валидация JSON схемы
- ✅ Проверка времени ответа

 ## 🔗 Связанные проекты

### 📱 Полный цикл тестирования:
- [🛒 Тестирование интернет-магазина](https://github.com/QA-Vitaly/web_testing)
- [🌐 API тестирование](https://github.com/QA-Vitaly/api_testing) - этот проект
- [🐬 Тестирование БД](https://github.com/QA-Vitaly/MySQL)
- [🔍 Charles Proxy](https://github.com/QA-Vitaly/Charles-Proxy)
