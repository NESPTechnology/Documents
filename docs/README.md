---
lang: zh-CN
title: Hello Nesp Open Documents
description: VuePress Testing
---

# Hello Nesp Open Documents


## Steps 
```shell
git init
```

```shell
npm init
```

```shell
npm install -D vuepress@next
```

Add some scripts on ``` package.json ```

```JSON
{
  "scripts": {
    "docs:dev": "vuepress dev docs",
    "docs:build": "vuepress build docs"
  }
}
```

```shell
echo 'node_modules' >> .gitignore
echo '.temp' >> .gitignore
echo '.cache' >> .gitignore
```


```shell
mkdir docs
echo '# Hello VuePress' > docs/README.md
```

```shell
npm run docs:dev
```
