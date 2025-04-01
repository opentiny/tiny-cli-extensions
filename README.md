# tiny-cli-extensions：TinyCLI 扩展

## tiny-cli-toolkits：TinyCLI 脚手架套件

套件是特定业务的标准化开发解决方案，一条命令即可完成项目的初始化；套件命令覆盖从项目初始化，到代码发布上线等流程。

插件列表：

- `@opentiny/tiny-toolkit-dev`：用于开发tiny-cli套件和插件的开发套件。详情可查看 [`dev` 套件文档](https://opentiny.design/tiny-cli/docs/toolkits/dev)
- `@opentiny/tiny-toolkit-pro`：开箱即用的中后台前端/设计解决方案。详情可查看 [`pro` 套件文档](https://opentiny.design/tiny-cli/docs/toolkits/pro)
- `@opentiny/tiny-toolkit-docs`：用于开发组件库官网的套件。详情可查看 [`docs` 套件文档](https://opentiny.design/tiny-cli/docs/toolkits/docs)

如果你想开发自定义套件，可以参考文档：[开发 TinyCLI 套件](https://opentiny.design/tiny-cli/docs/dev/toolkit)

## tiny-cli-plugins：TinyCLI 命令行插件

插件专注于某个单一的功能，解决工作中零散、 重复的任务。任意目录执行，开箱即用。

插件列表：

- `@opentiny/tiny-plugin-link`：用于快速调试本地node_modules中的依赖包的插件。详情可查看 [`link` 插件文档](https://opentiny.design/tiny-cli/docs/plugin/link)
- `@opentiny/tiny-plugin-hwc`：用于快速管理和访问华为云服务资源的插件。详情可查看 [`hwc` 插件文档](https://opentiny.design/tiny-cli/docs/plugin/hwc)
- `@opentiny/tiny-plugin-lint`：eslint+prettier 代码规范及格式化插件。详情可查看 [`lint` 插件文档](https://opentiny.design/tiny-cli/docs/plugin/lint)

如果你想开发自定义插件，可以参考文档：[开发 TinyCLI 插件](https://opentiny.design/tiny-cli/docs/dev/plugin)
