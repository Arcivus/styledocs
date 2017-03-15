## Блок-элемент

### .block-item

Блок, соответствующий какому-либо элементу\(фильтру, сортировке, подборке и т.п.\). Данные блоки, как правило, можно перетаскивать и через них открыть настройки соответствующих элементов.

![](/assets/block-items.png)

```
<div class="block-item">
    <div class="block-item-header">
        <span class="block-item-title">Новая страница</span>
        <a href="" class="block-item-close"></a>
    </div>
    <-- Здесь можно разместить доп. информацию в скрытых инпутах. Например -->
    <input type="hidden" value="{{ filter.guid }}" name="settings[filters][{{ filter.guid }}][guid]">
    <-- -->
    <div class="block-item-content">
        <button class="btn_green">{{ 'Настройки'|i18n }}</button>
    </div>
</div>
```



