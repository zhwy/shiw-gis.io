# CustomTreeComposite

## Props

<!-- @vuese:CustomTreeComposite:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|model|-|`Object`|`true`|-|
|activeKey|-|`String` /  `Number`|`false`|-|
|dragoverKey|-|`String`|`false`|-|
|first|-|`Boolean`|`false`|false|
|props|-|`Object`|`false`|{"title":"title","children":"children","key":"key"}|
|filter|-|`String`|`false`|-|
|disabled|-|`Boolean`|`false`|false|
|checkbox|-|`Boolean`|`false`|false|
|radio|-|`Boolean`|`false`|false|
|enableDrag|-|`Boolean`|`false`|false|
|draggableFilter|-|`Function`|`false`|function () {
  return this.enableDrag;
}|
|enableTitleEditting|-|`Boolean`|`false`|false|
|upOrDown|-|`String`|`false`|-|

<!-- @vuese:CustomTreeComposite:props:end -->


## Events

<!-- @vuese:CustomTreeComposite:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|nodeDblClick|-|-|
|nodeClick|-|-|
|`evtName`|-|-|
|toggleNode|-|-|
|saveTitle|-|-|
|whenDrop|-|-|
|itemDragover|if (this.model.type == LayerType.LayerGroupCollection) { e.preventDefault(); }|-|
|rightClick|-|-|

<!-- @vuese:CustomTreeComposite:events:end -->


