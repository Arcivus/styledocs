## Контейнер группы

### .group-container

Блок, используемый для расположения более крупной группы. Расстояние между этим и другими блоками будет немного больше, а лейбл-блоки и блоки компонентов внутри, напротив, будут распологаться немного кучнее.

![](/assets/group-container.png)

```
<div class="group-container">
    <h4 class="h4">Тэги</h4>
    <div class="label-block">
        <select></select
    </div>
    <div class="label-block">
        <select></select
    </div>
    <Checkbox class="component__root"></Checkbox>
</div

<label class="label-block">
    <span class="label-text">Количество на страницу</span>
    <input type="text" name="settings[per_page]" value="{{ settings.per_page }}">
</label>
```



