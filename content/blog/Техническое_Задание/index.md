---
title: Техническое Задание
summary: ТЗ
date: 2025-04-04
image:

authors:
  - Кадров Виктор Максимович
  - Оганнисян Давит Багратович
---


## 1. ОБЩИЕ ПОЛОЖЕНИЯ

### 1.1. НАИМЕНОВАНИЕ И УСЛОВНОЕ ОБОЗНАЧЕНИЕ РАБОТЫ

Наименование работы: Разработка приложения-генератора задач и управления проектами на основе шаблонов для Jira Software
Условное обозначение работы: "Jira Task Generator"

### 1.2. НАИМЕНОВАНИЕ ПРЕДПРИЯТИЯ ИСПОЛНИТЕЛЯ И ЗАКАЗЧИКА

Заказчик: АО Сбербанк
Исполнитель: ООО Рога и копыта

### 1.3. СРОКИ ВЫПОЛНЕНИЯ

Начало работ: 01.04.2025
Окончание работ: 01.06.2025

### 1.4. ОСОБЫЕ УСЛОВИЯ

Настоящее Техническое задание может уточняться и дополняться в процессе выполнения работ. Все изменения должны быть согласованы сторонами.

## 2. НАЗНАЧЕНИЕ РАЗРАБОТКИ

Целью разработки является создание веб-сервиса, интегрируемого с Jira Software, который позволит автоматизировать создание задач, учитывать нагрузку команды и распределять ресурсы наиболее эффективно. Основные функции приложения:
Генерация задач на основе шаблонов
Автоматическое распределение задач между участниками
Учет загрузки сотрудников
Интеграция с Jira Software
Гибкая система корректировки и редактирования задач

## 3. ТРЕБОВАНИЯ К ПРОГРАММЕ ИЛИ ПРОГРАММНОМУ ИЗДЕЛИЮ

### 3.1. ТРЕБОВАНИЯ К ФУНКЦИОНАЛЬНЫМ ХАРАКТЕРИСТИКАМ

#### 3.1.1. Общие требования

Приложение должно обеспечивать:
Высокую производительность и стабильность работы
Удобный и интуитивно понятный интерфейс
Гибкость в настройке параметров задач

#### 3.1.2. Основные функции

Приложение должно включать следующие модули:
Модуль генерации задач: создание задач на основе шаблонов
Модуль управления проектами: распределение задач по сотрудникам
Модуль интеграции с Jira Software: синхронизация данных
Модуль отчетности: анализ загрузки команды и эффективности выполнения задач
Модуль редактирования: возможность корректировки автоматически созданных задач

### 3.2. ТРЕБОВАНИЯ К НАДЕЖНОСТИ

Система должна обеспечивать стабильную работу с доступностью не менее 99.5%
Время восстановления после сбоя – не более 10 минут
Регулярное резервное копирование данных

### 3.3. ТРЕБОВАНИЯ К ТЕХНИЧЕСКИМ СРЕДСТВАМ

Серверная часть: Golang >= 1.24
Клиентская часть: React >=16.0

### 3.4. ТРЕБОВАНИЯ К ПРОГРАММНОЙ СОВМЕСТИМОСТИ

Поддержка API Jira Software
Совместимость с REST API
Поддержка OAuth 2.0 для аутентификации

## 4. ТРЕБОВАНИЯ К ПРОГРАММНОЙ ДОКУМЕНТАЦИИ

При создании ПО должны быть оформлены следующие документы:

Руководство системного программиста (ГОСТ 19.503-79);
Руководство оператора (ГОСТ 19.505-79);
Программа и методика испытаний (ГОСТ 19.301-79).
