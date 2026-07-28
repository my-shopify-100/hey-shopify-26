
|本期版本|上期版本
|:---:|:---:
`Fri Oct  3 00:34:53 CST 2025` | -

* `layout/theme.liquid`

```ruby
{{ content_for_header }}
{{ content_for_layout }}
```


## Support template-specific CSS selectors


```html
<body className="template-{{ template.name }}">
```

## Ref

* [Layouts - Overview](https://shopify.dev/docs/storefronts/themes/architecture/layouts)

