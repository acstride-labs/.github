<div align="center">

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/logo.svg" width="100" height="100" alt="Логотип AC-Stride">

# AC-Stride

**Условия, код и тесты. Вместе в VS Code.**

[Сайт](https://acstride.com/ru) · [Скачать](https://github.com/acstride-labs/codeforces-workbench/releases) · [Документация](https://github.com/acstride-labs/codeforces-workbench#readme) · [Обсуждения](https://github.com/orgs/acstride-labs/discussions)

[English](https://github.com/acstride-labs/.github/blob/main/profile/README.md) | [简体中文](https://github.com/acstride-labs/.github/blob/main/profile/README.zh-CN.md) | [日本語](https://github.com/acstride-labs/.github/blob/main/profile/README.ja.md) | **Русский**

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/workflow.svg" width="100%" alt="Рабочий процесс AC-Stride: импорт задачи, чтение условия, написание кода и проверка">

</div>

## Рабочее пространство для контестов

AC-Stride — набор инструментов для соревнований Codeforces и повседневной практики. Импортируйте задачи в редактор, пишите на привычном языке и проверяйте решения рядом с условием.

| | Возможности |
| --- | --- |
| **Импорт и чтение** | Добавьте целый контест Codeforces, отдельную задачу или создайте локальную. Условия и примеры загружаются автоматически. |
| **Привычный язык** | C++, Python, Java и Kotlin: отдельные исходники, шаблоны и проверка окружения. Расширения и сочетания клавиш VS Code работают как обычно. |
| **Тесты и сравнение** | Запускайте примеры и собственные тесты, просматривайте stdout, stderr и первое различие в выводе. Ограничивайте время или останавливайте выполнение. |
| **Ход соревнования** | Просматривайте историю отправок, вердикты и таблицу результатов. Копируйте код и открывайте страницу отправки либо отправляйте из редактора после входа и подтверждения. |
| **Перевод по запросу** | Подключите своего AI-провайдера для ручного или автоматического перевода условий. Настройте язык, промпт и необязательный локальный LRU-кэш запросов. |

Интерфейс доступен на английском, упрощённом китайском, японском и русском языках.

## Начало работы

1. **Установите расширение.** Скачайте VSIX для своей платформы из [Releases](https://github.com/acstride-labs/codeforces-workbench/releases) и выполните **Extensions: Install from VSIX...** в VS Code.
2. **Проверьте инструменты.** Откройте доверенную локальную папку. В **настройках AC-Stride** выберите язык по умолчанию и проверьте компилятор или среду выполнения.
3. **Выберите задачу.** Импортируйте контест или задачу Codeforces либо создайте локальную. Откройте условие, напишите решение и запустите тесты.

Инструменты Codeforces входят в расширение — отдельно устанавливать CF Tool не нужно. Компилятор или среду выполнения для решений установите самостоятельно. Для Java нужен JDK, для Kotlin — ещё и компилятор Kotlin.

> **Предварительная версия:** вход и автоматическая отправка экспериментальны и могут блокироваться проверкой сайта Codeforces. Публичные задачи и локальная практика доступны без входа. Автоматическая отправка всегда требует подтверждения.

## Проекты

| Проект | Назначение |
| --- | --- |
| [VS Code Extension](https://github.com/acstride-labs/codeforces-workbench) | Рабочее пространство с условиями, решениями, тестами и информацией о контестах. |
| [CF Tool](https://github.com/acstride-labs/codeforces-client) | Клиент Codeforces и CLI для загрузки задач, данных о соревнованиях и отправки решений. |
| [Website](https://github.com/acstride-labs/acstride-web) | Описание продукта, загрузки и руководства для начала работы. |

## Вопросы, идеи и ошибки

- **Вопросы:** задавайте их в [Q&A](https://github.com/orgs/acstride-labs/discussions/categories/q-a).
- **Предложения:** делитесь ими в [Ideas](https://github.com/orgs/acstride-labs/discussions/categories/ideas).
- **Ошибки:** создайте issue в репозитории [расширения](https://github.com/acstride-labs/codeforces-workbench/issues), [CF Tool](https://github.com/acstride-labs/codeforces-client/issues) или [сайта](https://github.com/acstride-labs/acstride-web/issues). Укажите шаги воспроизведения, платформу, версию и логи без секретных данных.
- **Обновления:** следите за [Announcements](https://github.com/orgs/acstride-labs/discussions/categories/announcements) и [историей изменений](https://github.com/acstride-labs/codeforces-workbench/blob/master/CHANGELOG.md).
