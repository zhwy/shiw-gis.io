# RightPanel

右侧信息面板组件

## Props

<!-- @vuese:RightPanel:props:start -->
|Name|Description|Type|Required|Default|
|---|---|---|---|---|
|panelData|-|`Object`|`true`|-|
|getLayer|-|`Function`|`true`|-|

<!-- @vuese:RightPanel:props:end -->


## Events

<!-- @vuese:RightPanel:events:start -->
|Event Name|Description|Parameters|
|---|---|---|
|close|if (this.panelData.type == LayerType.VectorCollection && this.panelData.layerBorder.coordinate.length == 0) { this.showMessage('请绘制边界或删除此图层！'); } else {|-|
|changeTitle|-|-|

<!-- @vuese:RightPanel:events:end -->


