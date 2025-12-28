# Практическая работа №1

## Цель работы
Настройка среды разработки Android Studio, изучение структуры проекта, работа с базовыми макетами и ресурсами, реализация обработки событий нажатия.

## Задание 1. Настройка среды и создание проекта
Создан проект `Lesson1` с минимальной версией SDK API 26 (Android 8.0) и целевой API 33. Проверена работа эмулятора Pixel 6.

<img width="1488" height="1116" alt="image" src="https://github.com/user-attachments/assets/57d82630-293a-4e76-80bb-9bf20a5cb344" />

## Задание 2. Работа с макетами (Module: layouttype)
Изучены основные типы макетов. В модуле созданы файлы разметки для демонстрации группировки элементов.

### LinearLayout и TableLayout
Реализована вложенность линейных макетов и верстка таблицы.

| LinearLayout | TableLayout |
|:---:|:---:|
| <img width="471" height="327" alt="image" src="https://github.com/user-attachments/assets/91f272a7-b500-4849-b500-7e84c9b484da" /> | <img width="477" height="323" alt="image" src="https://github.com/user-attachments/assets/8213c08e-30d3-4e24-b07a-c3fc4b832a77" /> |

## Задание 3. Контрольные элементы и ресурсы (Module: control_lesson1)
Создан экран "Контакты" с использованием `ConstraintLayout`. Изучена работа с ресурсами и привязка элементов к краям экрана.

<img width="1481" height="1112" alt="image" src="https://github.com/user-attachments/assets/69420371-75b8-4a2b-a043-da43fdedee6a" />

## Задание 4. Ориентация экрана (Module: control_lesson1)
Реализована адаптивная верстка.
*  Portrait : элементы расположены списком.
*  Landscape: элементы перестраиваются в таблицу, чтобы помещаться на экране.

| Портретная ориентация | Альбомная ориентация |
|:---:|:---:|
| <img width="494" height="508" alt="image" src="https://github.com/user-attachments/assets/d4d8493e-a41d-4944-8094-e5edd4c677a3" /> | <img width="656" height="323" alt="image" src="https://github.com/user-attachments/assets/d2ba62de-82a0-42c1-99e8-5fc1f8a78961" /> |

## Задание 5. Обработка событий (Module: ButtonClicker)
Реализована логика взаимодействия с пользователем в `MainActivity.java` и `activity_main.xml` двумя способами:
1.  View.OnClickListener для кнопки "Who Am I?" (изменение текста).
2.  android:onClick для кнопки "It Is Not Me" (всплывающее сообщение Toast).

<img width="466" height="290" alt="image" src="https://github.com/user-attachments/assets/b0a7e20d-3802-4b24-80a4-3d3017a6cdcf" />
