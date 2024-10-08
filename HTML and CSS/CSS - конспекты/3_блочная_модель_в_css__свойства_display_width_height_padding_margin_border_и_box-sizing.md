## Блочная модель в CSS 📐

### Введение в блочную модель 📖

Блочная модель в CSS представляет собой основополагающий механизм, который отвечает за расчет размеров элементов на веб-странице. Она помогает понять, как различные свойства влияют на размеры и расположение элементов. Чтобы увидеть, как это работает, вы можете воспользоваться инструментом разработчика, известным как DevTools. Этот инструмент доступен в любом современном браузере и станет вашим верным компаньоном в изучении CSS.

Чтобы открыть DevTools, достаточно нажать клавиши `F12` или щелкнуть правой кнопкой мыши по любой части страницы и выбрать пункт "Инспект". На начальном этапе вам будет достаточно вкладки "Elements", где можно анализировать как разметку, так и стили элементов.

### Инструменты для анализа 🤔

Когда мы хотим исследовать блочную модель конкретного элемента, например, квадрата, нам нужно его выделить. Это можно сделать, выбрав нужный тег в разметке или воспользовавшись режимом точечного выделения, нажав на кнопку слева от названия вкладки "Elements". Также можно использовать комбинацию клавиш `Ctrl + Shift + C`.

После выбора элемента, схему его блочной модели можно увидеть в нижней части DevTools, в вкладках "Styles" или "Computed". Блочная модель включает в себя несколько важных свойств:

- **`width`** и **`height`** — ширина и высота элемента.
- **`padding`** — внутренние отступы, которые отделяют содержимое от краев элемента.
- **`border`** — рамка, окружающая элемент.
- **`margin`** — внешние отступы, создающие пространство между элементами.

### Основные свойства блочной модели 📏

Свойства `width` и `height` задают размеры контентной области элемента. Под контентной областью понимается пространство, отведенное под содержимое, которое мы поместили внутрь элемента. Например, если у нас есть текст "Я-квадрат", именно его размеры и будут влиять на размеры блока.

Каждый элемент имеет свойство **`display`**, которое определяет его тип отображения. По умолчанию для тега `div` это значение — **`block`**. Это означает, что элемент будет занимать всю доступную ширину. При этом высота будет автоматически подстраиваться под содержимое.

### Правила работы с размерами 📏

Важно помнить, что задавать фиксированные размеры элементам — это плохая практика. Если вы установите конкретные значения для `width` и `height`, это может привести к проблемам, если содержимое элемента изменится. Например, если мы добавим больше текста в блок, он может вылезти за пределы заданных размеров.

Вот пример кода, где фиксированные размеры могут вызвать проблемы:

```css
.box {
    width: 200px;
    height: 100px;
    border: 1px solid black;
}
```

Когда добавим больше текста, блок будет выглядеть "сломленным", так как содержимое не поместится в заданные размеры.

> [!info]
>### Рекомендация 📌
> Всегда старайтесь использовать `auto` для высоты и ширины, чтобы избежать коллизий в верстке.

### Различия между блочными и строчными элементами 📊

Помимо блочного типа отображения, существуют и строчные элементы. Рассмотрим, к примеру, тег `span`. По умолчанию его значение для свойства `display` — **`inline`**. Это означает, что ширина элемента будет равна ширине его содержимого, а высота — высоте внутреннего контента. 

Строчным элементам нельзя задавать явные значения ширины и высоты; если вы попробуете это сделать, они просто не сработают. При этом, если мы проинспектируем элемент с помощью DevTools, то увидим, что свойства `width` и `height` отображаются тускло, что указывает на их неэффективность для `inline` элементов.

### Строчно-блочные элементы и их возможности ⚙️

Если изменить значение свойства `display` на **`inline-block`**, мы получаем строчно-блочный элемент. Он, как и `inline`, автоматически подстраивает свои размеры под содержимое, но, в отличие от `inline`, ему можно задавать специфические значения ширины и высоты.

Вот пример:

```css
.inline-block {
    display: inline-block;
    width: 150px;
    height: 50px;
    border: 1px solid blue;
}
```

### Скрытие элементов с помощью display.none ❌

Существует также значение **`none`** для свойства `display`, которое полностью скрывает элемент со страницы, хотя он и остается в разметке. Это свойство часто используется во фронтенде, но важно помнить, что оно не анимируется. Для создания анимаций появления и исчезновения элементов лучше использовать свойства `opacity` и `visibility`, но об этом мы поговорим в следующих уроках.

---

## Свойства блочной модели в CSS 📏

### Понимание свойства `display` 🖥️

Свойство `display` в CSS имеет больше значений, чем просто "блок", "инлайн" и "инлайн-блок". Однако для текущего урока важно сосредоточиться именно на этих трех типах отображения. Они служат основой для понимания дальнейших свойств в блочной модели.

### Внутренние отступы: `padding` 🛡️

Свойство `padding` задает внутренние отступы элемента. По умолчанию эти отступы добавляются к ширине и высоте элемента, влияя на его фактический размер. 

Представьте, что у нас есть блок с заданной шириной и высотой по 200 пикселей. Если мы зададим внутренние отступы в 15 пикселей сверху и снизу и 40 пикселей слева и справа, то фактическая ширина элемента будет равна:

```css
width = 200px + 40px (padding-left) + 40px (padding-right) = 280px
```

А высота — 

```css
height = 200px + 15px (padding-top) + 15px (padding-bottom) = 230px
```

Таким образом, важно помнить, что внутренние отступы по умолчанию являются частью ширины и высоты элементов.

### Рамка: `border` 📏

Свойство `border` добавляет рамку вокруг элемента. Синтаксис этого свойства включает ширину рамки, тип линии и ее цвет. Например:

```css
border: 10px solid red;
```

Рамка также влияет на размеры элемента, так что итоговая ширина с учетом рамки будет:

```css
width = 280px (ширина с padding) + 10px (border-left) + 10px (border-right) = 300px
```

А высота:

```css
height = 230px (высота с padding) + 10px (border-top) + 10px (border-bottom) = 250px
```

### Внешние отступы: `margin` 🌌

Свойство `margin` отвечает за внешние отступы элемента. В отличие от `padding`, внешние отступы не добавляются к фактическим размерам элемента, но они влияют на то, сколько места он занимает на странице. 

Представьте элемент с классом `box` и заданным значением `margin: 50px`. Это создаст отступы в 50 пикселей со всех сторон, отталкивая соседние элементы на указанное расстояние. 

### Важность `box-sizing` 📦

Свойство `box-sizing` меняет формулу расчета фактической ширины и высоты элемента. Когда вы устанавливаете `box-sizing: border-box`, размеры элемента теперь будут равны заданным значениям `width` и `height`, независимо от `padding` и `border`. 

Например, если у вас есть два одинаковых элемента, но у второго задан класс `normal-size` с `box-sizing: border-box`, то его размеры будут выглядеть следующим образом:

```css
.normal-size {
    box-sizing: border-box;
    width: 200px;
    height: 200px;
    padding: 15px;
    border: 10px solid black;
}
```

Теперь фактическая ширина и высота второго элемента останутся 200 пикселей, поскольку внутренние отступы и рамка будут включены в расчет.

>[!info]
>### Запомните! 📝
>Существует два значения для `box-sizing`: 
>1. `content-box` - значение по умолчанию.
>2. `border-box` - более удобное для работы, так как включает `padding` и `border` в заданные размеры.

### Заключение 🎓

В этом уроке мы узнали о блочной модели в CSS и её свойствах, таких как `display`, `padding`, `border`, `margin` и `box-sizing`. Эти свойства помогут вам лучше контролировать размеры и расположение элементов на странице. На следующем занятии мы углубимся в тему внутренних и внешних отступов, а также рассмотрим понятие схлопывания отступов.