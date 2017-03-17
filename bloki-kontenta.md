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

### .read\_\_more.read\_\_more\_\_show

Блок который по умолчанию свёрнут, при клике на "дополнительные настройки" разворачивается/сворачивается обратно.

![](/assets/dropdown.jpg)

```
<div class="read__more read__more__show">
    <div class="read__more__container">
        <---КОНТЕНТ--->
    </div>
    <a href="" class="read__more__active">{{ "дополнительные настройки"|i18n }}</a>
</div>
```

## Древо

### .cms\_tree

Генерится JS'ом, для правильного отображения родительский блок должен иметь класс **.cms\_tree**

![](/assets/tree.png)

