# Rime 输入法配置

个人使用的 Rime 输入法配置，基于 [雾凇拼音](https://dvel.me/posts/rime-ice/) 方案。

## 安装 Rime

- macOS: [鼠须管 Squirrel](https://rime.im/)
- Windows: [小狼毫 Weasel](https://rime.im/)
- Linux: [中州韵 IBus Rime](https://rime.im/)

## 配置管理

使用 [东风破 plum](https://github.com/rime/plum) 管理配置。

## 主要特性

- 输入方案：雾凇拼音 (rime_ice)
- 英文输入：Melt English (melt_eng)
- 拼音加 radical：radical_pinyin
- 自定义词组：custom_phrase.txt

## 文件说明

| 文件 | 说明 |
|------|------|
| `squirrel.yaml` | 鼠须管前端配置，包含外观主题设置 |
| `weasel.yaml` | 小狼毫前端配置 |
| `default.yaml` | 默认配置 |
| `rime_ice.schema.yaml` | 雾凇拼音方案配置 |
| `rime_ice.dict.yaml` | 雾凇拼音词库 |
| `custom_phrase.txt` | 自定义词组 |
| `user.yaml` | 用户配置 |

## 外观主题

当前使用自定义主题 `purity_of_form_custom`，基于「纯粹的形式」(Purity of Form) 进行了调整。

主要调整：
- 更柔和的配色
- 圆角半径：3px
- 字体：Avenir

## 同步

配置使用 Git 同步，可跨设备保持一致的输入体验。

## 参考

- [Rime 官网](https://rime.im/)
- [雾凇拼音文档](https://dvel.me/posts/rime-ice/)
- [鼠须管配置指南](https://github.com/LEOYoon-Tsaw/Rime_collections/blob/master/鼠鬚管介面配置指南.md)
- [鼠须管内置皮肤展示](https://github.com/NavisLab/rime-pifu)
- [rime-squirrel-macos-color-scheme](https://github.com/lonr/rime-squirrel-macos-color-scheme)
