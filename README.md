# 开发流程

<!-- 先发布测试环境再往正式环境发布 -->

- 发布前如果新建文件记得删除package.json 的private
```html
<!-- 初始化 -->
npx changeset init

<!-- 版本迭代 -->
npm run changeset

<!-- 生成changelog -->
npm run changeset:version

<!-- 发布版本 -->
npm run publish

```


```html

<!-- alpha beta rc -->
pnpm changeset pre enter [beta]

<!-- 退出 -->
pnpm changeset pre exit


```