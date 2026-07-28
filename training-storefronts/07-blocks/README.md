

## Blocks



* `Theme blocks`、`Section blocks`



## Theme blocks

* 要使此块显示在主题编辑器的块选择器中，您需要[添加块预设 ](https://shopify.dev/docs/storefronts/themes/architecture/blocks/theme-blocks?extension=liquid#add-a-block-preset)。
* 部分可以在本地定义块或选择支持主题块，但不能同时支持两者。



```
{% content_for 'blocks'}
```

```
"blocks": [{"type": "@theme"}]
```





* 对于接受类型为 @theme 的块的块和部分，所有带下划线前缀的块都将被排除在块选择器中



## Static Blocks



```
{% content_for "block", type: '<type>', id: "<id>"%}
```





## Ref

* [Blocks](https://shopify.dev/docs/storefronts/themes/architecture/blocks)