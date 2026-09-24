<p align="center">
  <img src="./assets/profile-banner.svg" width="100%" alt="Artem Simonyan — Android / Kotlin. Студент РТУ МИРЭА." />
</p>

<p align="center">
  <a href="https://github.com/ASimonyan1/studyflow-android"><b>Android-проект</b></a>
  &nbsp; / &nbsp;
  <a href="https://github.com/ASimonyan1/studyflow-android/blob/main/docs/WALKTHROUGH.md"><b>Архитектура</b></a>
  &nbsp; / &nbsp;
  <a href="mailto:artemsimonan81@gmail.com"><b>Связаться</b></a>
</p>

<br />

### Привет, я Артём

Учусь на **2 курсе РТУ МИРЭА**, направление — «Системная и программная инженерия». Развиваюсь в Android-разработке: мне интересно, как устроены приложения — от интерфейса и состояния до хранения данных и обработки ошибок.

В университете изучаю **C++, Python, Java и СиАОД — структуры и алгоритмы обработки данных**. Эту базу связываю с интересом к мобильной разработке: хочу понимать и пользовательский интерфейс, и алгоритмы, и работу приложения с данными.

**Сейчас ищу:** стажировку по Android-разработке, где смогу решать практические задачи и учиться у команды.

<p>
  <img src="./assets/languages.svg" width="100%" alt="Университетская подготовка: C++, Python, Java. Android-проект: Kotlin." />
</p>

<br />

### 01 / Проект

<a href="https://github.com/ASimonyan1/studyflow-android">
  <img src="./assets/studyflow-card.svg" width="100%" alt="StudyFlow — планировщик учебных задач. Kotlin, Compose, Room, MVVM. Открыть репозиторий." />
</a>

<p>
  <a href="https://github.com/ASimonyan1/studyflow-android/actions/workflows/android.yml"><img src="https://github.com/ASimonyan1/studyflow-android/actions/workflows/android.yml/badge.svg" alt="Android CI" /></a>
</p>

Создание и редактирование задач, поиск по предмету, фильтры и контроль сроков. Данные хранятся локально в Room; интерфейс получает обновления через Flow и ViewModel.

**[Код →](https://github.com/ASimonyan1/studyflow-android)** &nbsp; · &nbsp; **[Сборки и APK →](https://github.com/ASimonyan1/studyflow-android/actions)** &nbsp; · &nbsp; **[Как устроен проект →](https://github.com/ASimonyan1/studyflow-android/blob/main/docs/WALKTHROUGH.md)**

<sub>Учебный прототип подготовлен с помощью AI-инструментов. Возможности, ограничения и проверки описаны в README проекта.</sub>

<br />

### 02 / Университетская база

**РТУ МИРЭА · 2 курс · Системная и программная инженерия**

| Направление | Моя подготовка |
| :--- | :--- |
| **C++** | Изучаю в рамках университетской подготовки по программированию. |
| **Python** | Один из языков моей учебной практики. |
| **Java** | Изучаю в университете; хочу углублять знания в связи с Android-разработкой. |
| **СиАОД** | Структуры и алгоритмы обработки данных — часть моей университетской подготовки. |
| **Программная инженерия** | Интересуют ООП, организация кода, архитектура приложений и работа с данными. |

<br />

### 03 / Android: от теории к проекту

Технологии, с которыми разбираюсь на примере **StudyFlow**:

| Слой | Технологии | Что реализовано в проекте |
| :--- | :--- | :--- |
| **Интерфейс** | Jetpack Compose · Material 3 | Список задач, редактор, поиск, фильтры, светлая и тёмная темы |
| **Состояние** | ViewModel · Coroutines · Flow | Получение обновлений из базы и передача состояния в UI |
| **Данные** | Room · SQLite | Локальное хранение и работа без интернета |
| **Структура** | MVVM · Repository | Разделение интерфейса, состояния и операций с данными |
| **Качество** | JUnit · Android Lint | Проверки правил дат, поиска, сортировки и валидации |
| **Сборка** | Gradle · GitHub Actions | Автоматическая сборка debug APK и запуск проверок |

**Инженерные вопросы, которые мне интересны:** как выбирать структуру данных под задачу, сохранять состояние при повороте экрана, обрабатывать ошибки и проверять граничные случаи.

<br />

### 04 / Куда развиваюсь

- **Android:** глубже разобраться с жизненным циклом, управлением состоянием и асинхронной работой.
- **Алгоритмы:** укреплять университетскую базу и учиться оценивать сложность решений.
- **StudyFlow:** добавить напоминания и экспорт, расширить UI-тесты.
- **Работа с данными:** изучить синхронизацию и разрешение конфликтов при изменениях без сети.

<details>
<summary><b>Заглянуть внутрь StudyFlow</b></summary>

<br />

```text
Jetpack Compose UI
        ↓ действия     ↑ состояние
      ViewModel + Flow
             ↕
        Repository
             ↕
        Room / SQLite
```

[Разбор архитектуры и вопросы по коду](https://github.com/ASimonyan1/studyflow-android/blob/main/docs/WALKTHROUGH.md) · [Сценарии проверки приложения](https://github.com/ASimonyan1/studyflow-android/blob/main/docs/TESTING.md)

</details>

---

<p align="center">
  <b>Обсудим Android?</b><br />
  <a href="mailto:artemsimonan81@gmail.com">artemsimonan81@gmail.com</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/ASimonyan1">@ASimonyan1</a>
</p>
