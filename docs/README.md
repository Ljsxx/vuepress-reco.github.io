---
home: true
heroImage: /icon_vuepress_reco.png
heroImageStyle: {
  maxWidth: '200px',
  width: '100%',
  display: block,
  margin: '5rem auto 2rem',
  borderRadius: '1rem',
}
isShowTitleInHome: true
actionText: About
actionLink: /views/other/about
features:
- title: 过去
  details: 开发一款看着开心、写着顺手的 vuepress 博客主题。
- title: 当下
  details: 帮助更多的朋友节省时间去用心书写内容，而不是仅仅配置一个博客去孤芳自赏。
- title: 未来
  details: 吸引更多的朋友参与到开发中来，继续强大功能。
---

## 快速开始

**npx**

```
npx @vuepress-reco/theme-cli init my-blog
```

**npm**

```bash
# 初始化
npm install @vuepress-reco/theme-cli -g
theme-cli init my-blog

# 安装
cd my-blog
npm install

# 运行
npm run dev

# 编译
npm run build
```

**yarn**

```bash
# 初始化
yarn global add @vuepress-reco/theme-cli
theme-cli init my-blog

# 安装
cd my-blog
yarn install
```

## 多语言

|名称|语言代码|
|:-:|-|
|简中|`zh-CN`、`zh-SG`|
|繁中|`zh-HK`、`zh-MO`、`zh-TW`|
|日语|`ja-JP`|
|韩语|`ko-KR`|
|英语|`en-US` 及其他|

## 更新记录

[记录](https://github.com/vuepress-reco/vuepress-theme-reco/blob/develop/CHANGELOG.md)

## 贡献者

<Contributors user="vuepress-reco" repo="vuepress-theme-reco" :show-title="true"></Contributors>
<Contributors user="vuepress-reco" repo="vuepress-reco.github.io" :show-title="true"></Contributors>
