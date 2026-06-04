# template

uiauto.dev 插件模板项目。使用时先 fork 本项目，再在 fork 后的仓库中初始化。

## 使用步骤

1. **Fork 本项目**，得到你自己的插件仓库
2. 将 fork 后的项目克隆到本地插件目录：

   ```bash
   mkdir -p ~/.uiautodev/plugins
   git clone 你的仓库地址 ~/.uiautodev/plugins/你的插件名
   ```

3. 用 Claude 打开该项目，说 **"我要初始化项目"**，按 Claude.md 中的流程完成初始化
4. 之后修改 `app.ts` 和 `index.html`，编写插件逻辑和界面

## 本地调试

启动 uiauto.dev desktop 或 server 版本，`~/.uiautodev/plugins/` 下的插件会自动加载。开发时运行：

```bash
npm run dev
```

即可实时编译 `app.ts` 的改动。
