# Структурные блоки внутри контента окна

## Блок-модуль

### .config-module

Блок-контейнер с разделительной чертой снизу.

![](/assets/config-module.jpg)

```
<div class="config-module">
    <--- КОНТЕНТ --->
</div>
```

## Разворачиваемый блок

### .read\_\_more

Блок который по умолчанию свёрнут, при клике на "дополнительные настройки" разворачивается/сворачивается обратно.

![](/assets/dropdown.jpg)

```
<div class="read__more">
    <div class="read__more__container">
        <div class="read__more__content">
            <---КОНТЕНТ--->
        </div
    </div>
    <a href="" class="read__more__active show-closed">{{"Дополнительные настройки"|i18n}}</a>
    <a href="" class="read__more__active show-open">{{"Свернуть"|i18n}}</a>
</div>
```

## Древо

### .cms\_tree

Генерится JS'ом, для правильного отображения родительский блок должен иметь класс **.cms\_tree**

![](/assets/tree.png)

