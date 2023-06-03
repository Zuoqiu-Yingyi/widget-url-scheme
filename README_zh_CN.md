<div align="center">
<img src="./icon.png" style="width: 8em; height: 8em;">

---
[![GitHub 最新发行版本 (最新一次发行/预发行)](https://img.shields.io/github/v/release/Zuoqiu-Yingyi/widget-url-scheme?include_prereleases&style=flat-square)](https://github.com/Zuoqiu-Yingyi/widget-url-scheme/releases/latest)
[![GitHub 最新发行时间](https://img.shields.io/github/release-date/Zuoqiu-Yingyi/widget-url-scheme?style=flat-square)](https://github.com/Zuoqiu-Yingyi/widget-url-scheme/releases/latest)
[![GitHub 许可证](https://img.shields.io/github/license/Zuoqiu-Yingyi/widget-url-scheme?style=flat-square)](https://github.com/Zuoqiu-Yingyi/widget-url-scheme/blob/main/LICENSE)
[![GitHub 最后一次提交时间](https://img.shields.io/github/last-commit/Zuoqiu-Yingyi/widget-url-scheme?style=flat-square)](https://github.com/Zuoqiu-Yingyi/widget-url-scheme/commits/main)
![GitHub 仓库大小](https://img.shields.io/github/repo-size/Zuoqiu-Yingyi/widget-url-scheme?style=flat-square)
![查看次数](https://hits.b3log.org/Zuoqiu-Yingyi/widget-url-scheme.svg)
[![GitHub 发行版本下载次数](https://img.shields.io/github/downloads/Zuoqiu-Yingyi/widget-url-scheme/total?style=flat-square)](https://github.com/Zuoqiu-Yingyi/widget-url-scheme/releases)

---
简体中文 \| [English](./README.md)

---
</div>

# URL 协议

> 本项目从 [DiamondYuan/302](https://github.com/DiamondYuan/302) *[MIT License](https://github.com/DiamondYuan/302/blob/main/LICENSE)* 分叉, 感谢原作者 [DiamondYuan](https://github.com/DiamondYuan) :heart:

一个可将 URL Scheme 转换为 HTTP 302 重定向地址的挂件

## 相关参考文章

- [在任意网站支持 URL Scheme - 少数派](https://sspai.com/post/66896)
- [总结：url scheme 相关 · 语雀](https://www.yuque.com/deerain/gannbs/gmkp9w)

## 预览

![preview](https://cdn.jsdelivr.net/gh/Zuoqiu-Yingyi/widget-url-scheme/preview.png)

## 功能

- 将 `URL Scheme` 转换为 `HTTP URL`
  - 输入 `URL Scheme` 后单击 <kbd>复制</kbd> 按钮将转换后的 `HTTP URL` 写入剪贴板
  - 输入 `URL Scheme` 后单击 <kbd>回车</kbd> 键将转换后的 `HTTP URL` 写入剪贴板
- 将 `HTTP URL` 重定向至 `URL Scheme`
  - 在浏览器中访问 `HTTP URL` 将重定向至 `URL Scheme`
- 跟随全局主题更改颜色
- 跳转完成后自动关闭页签
- 勾选 `6806` 复选框以将超链接的端口设置为 6806 端口
  - 思源内核在使用随机端口号时会同时监听 `6806` 端口

## 开始

### 自动

该挂件已在[思源笔记社区集市](https://github.com/siyuan-note/bazaar)上架, 可直接在集市中安装

### 手动

1. 在 [Releases](https://github.com/Zuoqiu-Yingyi/widget-url-scheme/releases) 中下载发行包, 解压后放到[思源笔记](https://github.com/siyuan-note/siyuan)`<工作空间>/data/widgets/` 目录下
2. 在笔记中创建一个 `IFrame` 块, 地址填 `/widgets/widget-url-scheme` 即可

## 更改日志

[CHANGE LOG](./CHANGELOG.md)
