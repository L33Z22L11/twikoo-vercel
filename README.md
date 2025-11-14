# twikoo-vercel 去除 localhost 强制放行

避免开源项目的 Twikoo 实例被本地测试人员滥用。

https://github.com/twikoojs/twikoo/issues/808

需要在项目添加以下环境变量，以便应用 pnpm patch。

```
ENABLE_EXPERIMENTAL_COREPACK=1
```