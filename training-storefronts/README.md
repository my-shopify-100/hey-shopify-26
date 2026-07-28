
## 01-create

* 您还可以使用 `dev` 生成**预览链接**和开发主题的**主题编辑器**

## 02-architecture

* 不支持列出的子目录以外的子目录。
* 只需包含 `theme.liquid` 文件的`布局`目录即可将主题上传到 Shopify。


## 03-layouts

* `content_for_header`、`content_for_layout`


## 04-templates

* 分区文件必须在其架构中**定义预设** ，以支持使用主题编辑器添加到 JSON 模板。没有预设的分段文件应手动包含在 JSON 文件中，并且无法使用主题编辑器删除。
* 模板只能作为 JSON 或 Liquid 模板存在，不能同时存在两者
* 要渲染的分区文件的文件名，不带扩展名。
* 备用模版: `product.alternate.json`
* 呈现备用模版: `/products/example-product?view=alternate`


## 07-blocks

* 要使此块显示在主题编辑器的块选择器中，您需要[添加块预设 ]



## 10-config



* `settings_schema.json`、`settings_data.json`
* `theme_info`