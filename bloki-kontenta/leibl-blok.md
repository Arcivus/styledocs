## Лейбл-блок

### .label\_\_block

Блок для разделения компонентов в одном модуле

```
<div class="label__block">
    <--- КОНТЕНТ --->
</div>
```

## ![](/assets/label-block-default.png)

Базовый блок, состоящий из инпута с заголовком выглядит так:

```
<div class="label__block">
    <div class="label__text">Код элемента</div>
    <input type="text" value="" name="title">
</div>
```

Текст может быть как жирным, так и едва заметным, для этого используются классы **.strong** и _.weak_, соответственно

![](/assets/label-block-str-weak.png)

```
<div class="label__block">
    <div class="label__text"><span class="strong">Базовая сортировка</span> </span class="weak">sorting</span></div>
    <input type="text" value="" name="sorting">
</div>
```



