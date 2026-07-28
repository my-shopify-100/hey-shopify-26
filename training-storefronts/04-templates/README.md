|本期版本|上期版本
|:---:|:---:
`Fri Oct  3 00:44:58 CST 2025` | -

* Section files must define [presets](https://shopify.dev/docs/storefronts/themes/architecture/sections/section-schema#presets) in their schema(分区文件必须在其架构中定义[预设 ](https://shopify.dev/docs/storefronts/themes/architecture/sections/section-schema#presets))
* A template can only exist as a JSON or Liquid template,(模板只能作为 JSON 或 Liquid 模板存在，不能同时存在两者)
* **The filename of the section file to render, without the extension.(要渲染的分区文件的文件名，不带扩展名。)**

---

```json
{
	"sections": {},
	"order": []
}
```

## `custom css setting`


## Render an alternate template(使用备用模版)

```
# name.suffix.type
?view=[suffix]
```
## Ref

* [Templates - Overview](https://shopify.dev/docs/storefronts/themes/architecture/templates)
* [JSON templates](https://shopify.dev/docs/storefronts/themes/architecture/templates/json-templates)