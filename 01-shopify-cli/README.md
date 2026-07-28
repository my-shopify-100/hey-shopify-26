## Shopify CLI

|本期版本|上期版本
|:---:|:---:
`Mon Jul 27 21:29:01 CST 2026` | -

### Requirements

```bash
mise use -g node@22
apt-get install git git-lfs git-extras
```

### Installation

```bash
mise use -g npm:@shopify/cli@latest
shopify version
```

### ~~Upgrade Shopify CLI~~

```bash
# 立即升级
shopify upgrade

# 禁用自动升级
shopify config autoupgrade off
```

### ~~Usage reporting~~

```
SHOPIFY_CLI_NO_ANALYTICS=1
```


## Network proxy configuration


```bash
export SHOPIFY_HTTP_PROXY=http://127.0.0.1:7890
```






## Ref

- <https://shopify.dev/docs/api/shopify-cli>