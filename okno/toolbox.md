# Панель Toolbox

### .window\_\_toolbar

Панель управления, в отличии от  тулбара окна, находится внутри контента.

![](/assets/toolbox.jpg)

```
<div class="window__toolbar">
  <div class="window__toolbar__list" data-toolbox="settings">
  </div>
</div>
```

Кнопки в тулбокс добавляются JS'ом,  при этом параметр data-toolbox служит для идентификации конкретного тулбокса.

#### Пример добавления кнопки:

```
this.window.toolbox('settings').add(cms.core.i18n('Сохранить'), {id: '_save', events: {
  click: this.save.bind(this)
}});
```



