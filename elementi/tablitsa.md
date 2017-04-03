## Таблица

### .table\_\_input\_\_item

Блок для расположения заголовка и элемента на одной строке. Для корректного отображения должен находиться в блоке **.table\_\_input**

![](/assets/table__input.png)

```
<ul class="table__input">
    <--Заголовок и инпут-->
    <li class="table__input__item">
        <label class="table__input__label">
            <span class="label__text">Название движка</span>
            <input name="title">
        </label>
    </li>
    <--Заголовок и селект-->
    <li class="table__input__item">
        <label class="table__input__label">
            <span class="label__text">Тип данных</span>
            <span class="table__input__input">
                 <select></select>   
            </span>
        </label>
    </li>
    <--Заголовок и чекбоксы-->
    <li class="table__input__item">
        <label class="table__input__label">
            <span class="label__text">Тип данных</span>
            <span class="table__input__inpu category-checkbox">
                 <--Все чекбоксы сюда--> 
            </span>
        </label>
    </li>



</ul>
```

### .align-vertical

Если требуется выравнять контент строки по вертикали то этот класс следует добавить к .table\_\_input_\_\__label 

```
<li class="table__input__item">
    <label class="table__input__label align-vertical">
        <span class="label__text">Название движка</span>
        <input name="title">
    </label>
</li>
```

![](/assets/center.jpg)







