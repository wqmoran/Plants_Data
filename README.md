# Plants_Data 项目介绍

## 项目背景
Plants_Data 是从我开发的个人项目中衍生出来的开源数据集，目前处于项目初期，先提供科的中英文对照数据。随着个人项目的进展，我将开放更多与植物相关的数据集。

## 数据文件说明
本项目目前包含以下 JSON 文件：
- family.json：植物科的中英文对照数据。

### family.json 字段说明
- name: 科的拉丁学名，来源于 APG IV。
- name_cn: 科的中文名，方便中文用户识别和应用。
- show_name: 显示名称，结合拉丁学名和中文名，便于理解和参照。
- former_names: 曾用名数组，包含了该科历史上可能使用过的其他学名。
- is_fossil_based: 布尔值，标示此科是否基于化石记录。false 表示不是，true 表示是。

## 如何使用
你可以通过 Git 克隆或下载本项目，使用 JSON 文件中的数据进行植物科的查询或其他相关工作。

``` bash
git clone https://github.com/your-github-account/Plants_Data.git
```

## 贡献指南
感谢对 Plants_Data 项目的关注！如果你在使用数据中发现任何错误或不一致，或者有任何改进建议，我们非常欢迎你的反馈和贡献。

### 报告问题
如果你在数据中发现错误或其他问题，请通过以下方式告知我们：
- 在 GitHub 项目中创建一个 Issue，请尽可能详细地描述问题。

## 许可证
本项目采用 [MIT 许可证](https://opensource.org/licenses/MIT)。
