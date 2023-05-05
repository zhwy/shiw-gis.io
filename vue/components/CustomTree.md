# CustomTree

## Props

<!-- @vuese:CustomTree:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|compositeComponent|-|`String`|`false`|CustomTreeComposite|
|treeData|-|`Array`|`true`|-|
|treeProps|-|`Object`|`false`|{"title":"title","children":"children","key":"key","type":"type"}|
|filter|-|`String`|`false`|-|
|disabled|-|`Boolean`|`false`|false|
|enableDrag|-|`Boolean`|`false`|false|
|draggableFilter|-|`Function`|`false`|function () {
  return this.enableDrag;
}|
|enableTitleEditting|-|`Boolean`|`false`|false|
|dragExit|-|`Function`|`false`|() => {}|

<!-- @vuese:CustomTree:props:end -->


## Events

<!-- @vuese:CustomTree:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|itemDragover|-|-|
|nodeClick|-|-|
|nodeDblClick|-|-|
|whenDrop|-|-|
|rightClick|-|-|
|add|-|-|
|delete|-|-|
|play|-|-|
|more|-|-|
|toggleNode|-|-|
|saveTitle|-|-|

<!-- @vuese:CustomTree:events:end -->


