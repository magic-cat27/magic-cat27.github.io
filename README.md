# 张京鹏的个人主页

个人介绍与作品集，使用静态 HTML 和 CSS，无需构建。

## 目录

```text
index.html                 个人介绍页 / 网站入口
pages/
  portfolio.html           作品集
  steerrobot.html          SteerRobot Demo
  zhihu.html               知乎热榜截图
assets/
  css/                     公共样式与各页面样式
  images/                  头像、知乎截图、视频封面
  videos/steerrobot/        原始视频与浏览器兼容版
  papers/ai4math/           AI4MATH 论文
references/codingharness/   原 CodingDoc 文档备份
```

CodingHarness 的独立仓库：[magic-cat27/CodingHarness](https://github.com/magic-cat27/CodingHarness)。作品集直接链接到该仓库，`references/` 中保留的是原始文档备份。

## 本地预览

在仓库根目录运行：

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

打开 <http://127.0.0.1:8765/>。作品集地址为 <http://127.0.0.1:8765/pages/portfolio.html>。

## 修改内容

- 个人介绍与荣誉：`index.html`。
- 项目简介与按钮链接：`pages/portfolio.html`。
- 公共样式：`assets/css/styles.css`。
- 作品集、Demo、截图页的专用样式：`assets/css/` 下对应文件。
- 更新 Demo 时保留浏览器可播放的 `demo-web.mp4` 和封面 `demo-poster.jpg`。

页面使用相对路径；移动文件时需要同步更新页面中的链接、图片、样式与视频路径。

## 发布

目标仓库为 [magic-cat27/magic-cat27.github.io](https://github.com/magic-cat27/magic-cat27.github.io)。确认本地效果后再提交和推送。
