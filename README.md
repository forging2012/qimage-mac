
<div align=center>
    <p><img src="http://7xry05.com1.z0.glb.clouddn.com/201711271735_182.png" alt="qimage-mac"/></p>
    <a target="_blank" href="https://travis-ci.org/cdoco/grank" title="platform"><img src="https://img.shields.io/badge/platform-osx--64-lightgrey.svg"></a>
    <a target="_blank" href="https://github.com/jiwenxing/qiniu-image-tool/archive/v1.1-release.zip" title="download"><img src="https://img.shields.io/badge/download-3.43M%20v1.1-green.svg"></a>
    <a target="_blank" href="https://opensource.org/licenses/MIT" title="License: MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
</div>

___

**qimage-mac** 是一个 mac 中提升 markdown 贴图体验的实用小工具，基于 Alfred 实现，可以自定义快捷键，一键上传图片或截图至七牛云，获取图片的 markdown 引用至剪贴板，并自动粘贴到当前编辑器，使用简单方便。

## Changelog

- v1.1 - 2017.11 - 针对 [issue #4](https://github.com/jiwenxing/qiniu-image-tool/issues/4) 新增支持自定义文件名称的 workflow ：`support user-defined file name.alfredworkflow`    
特点：
  1. 上传本地图片则默认使用原图片名称
  2. 上传截图或网络图片时，会弹窗提示输入自定义图片名称

## Usage
详细的使用教程请参考：[使用alfred在markdown中愉快的贴图](http://jverson.com/2017/04/28/alfred-qiniu-upload/)     
windows版本请移步至：https://github.com/jiwenxing/qiniu-image-tool-win


## Features
- 支持jpg、png、bmp及gif等各种图片格式
- 支持截图及网络图片直接复制上传
- 支持各种其它格式本地文件上传，返回资源引用
- 上传失败或成功通知栏会有相应提示
- 使用简单，只需配置环境变量即可

## Requirements
**`Alfred with Powerpack`** **`qshell`** **`七牛账号`**

## Preview
1. 本地图片文件上传 <br/>
![](https://raw.githubusercontent.com/jiwenxing/qiniu-image-tool/master/res/local.gif)

2. 截图上传  <br/>
![](https://github.com/jiwenxing/qiniu-image-tool/blob/master/res/paste.gif?raw=true)

3. 其它文件上传  <br/>
![](https://raw.githubusercontent.com/jiwenxing/qiniu-image-tool/master/res/file.gif)



注：演示gif使用macdown及licecap制作


# License
[MIT License](https://raw.githubusercontent.com/jiwenxing/qiniu-image-tool/master/LICENSE).     
Copyright (c) 2017 Jverson






