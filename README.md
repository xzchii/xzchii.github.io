# xzchii

个人网站，用来记录技术、生活与思考：[xzchii.github.io](https://xzchii.github.io/)。

## 本地开发

```sh
pnpm install
pnpm dev
```

运行 `pnpm build` 构建静态站点，生成的文件在 `dist/`。

## 写文章

运行 `pnpm new-post <文件名>`，或在 `src/content/posts/` 中新建 Markdown 文件。站点标题、个人资料和导航链接在 `src/config.ts` 中维护；关于页内容在 `src/content/spec/about.md` 中维护。

## 项目来源

本站基于 [Astro](https://astro.build/) 和 [Fuwari](https://github.com/saicaca/fuwari) 构建。原项目的许可声明保留在 [LICENSE](LICENSE) 中。
