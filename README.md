# 简答题
## 1.谈谈你对工程化的初步认识，结合你之前遇到过的问题说出三个以上工程化能够解决问题或者带来的价值
### 前端工程化：
- 面临的问题是如何提高编码->测试->维护阶段的生产效率
- 一切提高效率、降低成本、质量保证为目的的手段都属于工程化

### 工程化带来的价值
- 模块化：将一个大文件拆分成相互依赖的小文件，再进行统一的拼装和加载。
- 组件化：从UI拆分下来的每个包含模板(HTML)+样式(CSS)+逻辑(JS)功能完备的结构单元。
- 规范化：制定开发规范，提高团队协作能力。
- 自动化：前端工程化的很多脏活累活都应该交给自动化工具来完成。


## 2.你认为脚手架除了为我们创建项目结构，还有什么更深的意义？
- 把自己常用的项目结构定义成一个小型的脚手架
- 能够快速生成新项目的目录模板
- 能够提升开发效率和开发的舒适性，减少重复编写代码

# 编程题
## 1.概述脚手架实现过程，并使用NodeJS完成一个自定义的小型脚手架工具
### 脚手架实现过程：
- 拉取模板
- 在目标文件创建项目
- 收尾清理

### 项目文件
- 脚手架文件路径：code/okii-cli
- 模板文件路径：https://github.com/linhui97/vue-template.git

## 2.尝试使用Gulp完成项目的自动化构建
- 项目文件路径：code/gulp-pages-boilerplate

## 3.使用Grunt完成项目的自动化构建
- 项目文件路径：code/grunt-pages-boilerplate