## Tooltip 文字提示

常用的文字提示组件

### 基础

:::demo 

Tooltip 组件

```js
render() {
  return (
    <div>
      <Tooltip title="tooltip top" style={{margin: '0 10px'}}><Button type="line">Tooltip Top</Button></Tooltip>
      <Tooltip title="tooltip right" style={{margin: '0 10px'}} placement="right"><Button type="success">Tooltip Right</Button></Tooltip>
      <Tooltip title="tooltip bottom" style={{margin: '0 10px'}} placement="bottom"><Button type="warning">Tooltip Bottom</Button></Tooltip>
      <Tooltip title="tooltip left" style={{margin: '0 10px'}} placement="left"><Button type="danger">Tooltip Left</Button></Tooltip>
    </div>
  )
}
```
:::

### Tooltip Attributes

| 参数 | 说明 | 类型 | 可选值 | 默认值 |
| ------- | ------- | ------- | ------- | ------- |
| title | 提示文字内容 | string | 字符串 | -- |
| placement | tooltip显示的位置 | string | top,right,bottom,left | top |
