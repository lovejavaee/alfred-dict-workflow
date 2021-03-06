# Alfred 查词扩展

多功能、快速、易用的 Alfred 查词扩展。

## 简介

* 支持的词典：
    * 系统词典，仅支持朗道英汉/汉英词典5.0
    * 有道在线词典
    * 爱词霸在线词典
    * 百度在线词典
* 支持英汉、汉英互查
* 支持音标，默认显示美式音标
* 使用系统 TTS 引擎发音
* 汉译英可复制英文解释
* 可使用快捷键进行词典切换
* 缓存查询结果，方便下次查询
* 支持快捷键取词

## 截图

![screenshot](https://github.com/liberize/alfred-dict-workflow/raw/master/screenshot.gif)

## 用法

如果没有安装朗道英汉/汉英词典5.0，请先[下载](http://pan.baidu.com/s/1qWx4mV6)，然后复制到 `~/Library/Dictionaries/` 目录。

关键词为 `dict`，默认使用系统词典，使用以下格式指定词典：

    dict {word} @ {dict}

词典代号及切换快捷键：

词典      | 代号        | 快捷键
-------- | ----------- | ---------
系统     | sys, system  | `⌘` `↩`
有道     | yd, youdao   |  `⌥` `↩`
爱词霸   | cb, iciba     | `⌃` `↩`
百度     | bd, baidu    | `⇧` `↩`

## 联系我

<liberize@gmail.com>
