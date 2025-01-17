### Компонент TreeView

Создать приложение для отображения иерархической структуры данных с возможностью раскрытия и скрытия вложенных элементов.

### Обзор:
+ [Описание](#descr-task);
+ [Запуск проекта в IDE](#start);
+ [Изображение проекта](#image);

### <a name="descr-task"></a> 📋 1. Описание:
  + Использовать React и TypeScript.
  + Использовать стейт-менеджер Effector или Redux Toolkit.
  + Реализовать компонент 'TreeView', который будет рекурсивно отображать данные, представленные в виде вложенных списков.

#### 2. Функциональные требования:
  + Компонент 'TreeView' должен принимать массив объектов, где каждый объект может содержать свойства name (название элемента) и children (массив вложенных элементов).
  +	Каждый элемент должен иметь кнопку для раскрытия/скрытия вложенных элементов.
  + Состояние раскрытых/скрытых элементов должно управляться через стейт-менеджер.

#### 3. Дополнительный критерий (необязательный):
  + Добавить анимацию для плавного раскрытия и скрытия вложенных элементов.
  + Реализовать сохранение состояния UI между сессиями пользователя с использованием localStorage / sessionStorage.


### <a name="start"></a> 🛠️ Запуск проекта в IDE:
Команды:
  + `npm i` - установит все зависимости.
  + `npm run dev` - запускает приложение в режиме разработки.
  + `npm run build` - сборка проекта, собирает файлы проекта в каталог dist.
  + `npm run preview` - запускает приложение в режиме production.
  + `npm run format` - запускает Prettier для форматирования файлов.
  + `npm run lint` - запускает ESLint для проверки ts,tsx файлов.

### <a name="image"></a> 🖼️ Изображение
<p align="center">
  <img src="https://github.com/AlexDyatlov/React-TreeView/blob/main/public/interface.png">
</p>