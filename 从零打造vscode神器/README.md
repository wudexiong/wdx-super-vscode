# 从零开始打造vscode 神器

## 基础功能（必备）

### 基础知识

#### VSCode Settings Sync 官方配置同步

> 参考文章： <https://juejin.cn/post/7066622158184644621>
> Settings Sync功能默认是关闭的，点击VSCode左下方的齿轮，开启Settings Sync功能

#### 工作区

> 参考文章： <https://zhuanlan.zhihu.com/p/187261089>

##### 插件

* Project Manager 配合工作区一起使用

* johnpapa.vscode-peacock 每个工作区拥有独立外观

#### 运行任务

> 参考文章：<https://juejin.cn/post/7035448197883363359>

##### 自定义快捷键

* 运行任务 `Ctrl + Alt + R`

## 基础插件

> 参考：
> <https://juejin.cn/post/6844903510685794318>
> <https://juejin.cn/post/6997186741866070023>

### 外观插件配置

* Solarized Dark VSCode 已经内置，使用了至少 5 年以上的主题，Vim 下的配置完全相同

* VSCode Great Icons 给不同类型的文件配置不同的图标，非常直观

* Fira Code 使用字体 配置说明<https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions>



### 风格检查配置

* ESLint

* StyleLint

* MarkdownLint

* EditorConfig 在项目根目录中设置`.editorconfig`文件

    `.editorconfig`:

    ```ini
    [*]
    end_of_line = lf
    charset = utf-8
    trim_trailing_whitespace = false
    insert_final_newline = true
    indent_style = space
    indent_size = 2

    [{*.yml,*.json}]
    indent_style = space
    indent_size = 2
    ```

### 识别代码

* Color Highlight 识别代码中的颜色，包括各种颜色格式

* Bracket Pair Colorizer 识别代码中的各种括号，并且标记上不同的颜

* TODO Highlight 各种 TODO、FIXME、HACK 之类的标记高亮

* Code Spell Checker 正确识记拼写各种单词

* Trailing Spaces 尾部空格删除插件

* DotENV `.env`文件代码高亮

* JSON to TS json转为TS申明

* koroFileHeader 生成注释

* Import Cost 依赖包大小提示

* Add jsdoc comments 给方法添加JSDoc

* Wrap Console Log Lite 快捷生成`console.log`输出代码

* Quokka.js  直接显示变量结果

* Path Intellisense  引入路径提示

* vscode-faker 生成虚假数据

* Regex Previewer 边写正则边看结果

* Color Picker 颜色选择器

* Sort Typescript imports import自动排序



* npm 运行 package.json 文件中定义的 npm 脚本，并根据 package.json 中定义的依赖项验证已安装的模块

* Live Sass Compiler SASS实时编译

* CodeMetrics 计算代码复杂度

### 服务类工具

* LiveServer 一键启动本地开发服务器

* Tabnine AI 人工智能代码完成工具

* REST Client  rest网络请求查看 visualstudio 代码中的响应。

* Markdown PDF markdown转PDF

### 代码仓库Git

* Git History 查看Git的历史，搜索，版本对比

* GitLens 无缝导航和浏览 Git 存储库

### 预览功能

* Image Preview 图片预览

* Draw.io integration 设计画画流程图


### 代码工具



## 参考资料

* vscode 官方文档  <https://code.visualstudio.com/docs>

