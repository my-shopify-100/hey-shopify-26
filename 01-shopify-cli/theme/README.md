## Shopify CLI Theme commands


|本期版本|上期版本
|:---:|:---:
`Tue Jul 28 16:46:16 CST 2026` | -



```bash
# 初始化新主题，将 Skeleton 克隆到本地
shopify theme init

# 在首次预览主题时，必须要设置 `--store` 参数
shopify theme dev --store {store-name}
# --host / --port

# 要查看自己当前链接的商店
shopify theme info

# 上传主题
shopify theme push --unpublished

# 发布主题
shopify theme publish
```

```bash
shopify theme pull --store {store-name}
```