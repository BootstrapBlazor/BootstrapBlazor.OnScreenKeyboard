## Blazor OnScreenKeyboard 屏幕键盘 组件

基于 [KioskBoard](https://github.com/furcan/KioskBoard)

### 示例

https://www.blazor.zone/onscreenkeyboards

https://blazor.app1.es/onscreenkeyboards

## 使用方法:

1. nuget包

    ```BootstrapBlazor.SignaturePad```

2. _Imports.razor 文件 或者页面添加 添加组件库引用

    ```@using BootstrapBlazor.Components```


3. Razor页面

    ```
    @using BootstrapBlazor.Components

    @code{
        string BindValue = "virtualkeyboard"; 
    }

    <input class="@ClassName"
              data-kioskboard-type="@KeyboardType.all.ToString()"
              data-kioskboard-specialcharacters="true"
              placeholder="全键盘" />
    <input class="@ClassName"
           data-kioskboard-type="@KeyboardType.keyboard.ToString()"
           data-kioskboard-placement="@KeyboardPlacement.bottom.ToString()"
           placeholder="字母键盘" />
    <input class="@ClassName"
           data-kioskboard-type="@KeyboardType.numpad.ToString()"
           data-kioskboard-placement="@(KeyboardPlacement.bottom.ToString())"
           placeholder="数字键盘" />
    <OnScreenKeyboard ClassName="@ClassName" />

    ```

4. 更多信息请参考

    Bootstrap 风格的 Blazor UI 组件库
基于 Bootstrap 样式库精心打造，并且额外增加了 100 多种常用的组件，为您快速开发项目带来非一般的感觉

    <https://www.blazor.zone>

    <https://www.blazor.zone/onscreenkeyboards>

----

## Blazor On-screen keyboard component


### Demo

https://www.blazor.zone/onscreenkeyboards

https://blazor.app1.es/onscreenkeyboards

## Instructions:

1. NuGet install pack 

    `BootstrapBlazor.OnScreenKeyboard`

2. _Imports.razor or Razor page

   ```
   @using BootstrapBlazor.Components
   ```
3. Razor page

    ```
    @code{
        string BindValue = "virtualkeyboard"; 
    }

    <input class="@ClassName"
           data-kioskboard-type="@KeyboardType.all.ToString()"
           data-kioskboard-specialcharacters="true"
           placeholder="Full Keyboard" />
 
    <input class="@ClassName"
           data-kioskboard-type="@KeyboardType.keyboard.ToString()"
           data-kioskboard-placement="@KeyboardPlacement.bottom.ToString()"
           placeholder="Keyboard" />

    <input class="@ClassName"
           data-kioskboard-type="@KeyboardType.numpad.ToString()"
           data-kioskboard-placement="@(KeyboardPlacement.bottom.ToString())"
           placeholder="Numpad" />
    ```

4.  More informations

    Bootstrap style Blazor UI component library
Based on the Bootstrap style library, it is carefully built, and 100 a variety of commonly used components have been added to bring you an extraordinary feeling for rapid development projects

    <https://www.blazor.zone>

    <https://www.blazor.zone/onscreenkeyboards>


---
#### Blazor 组件

[条码扫描 ZXingBlazor](https://www.nuget.org/packages/ZXingBlazor#readme-body-tab)
[![nuget](https://img.shields.io/nuget/v/ZXingBlazor.svg?style=flat-square)](https://www.nuget.org/packages/ZXingBlazor) 
[![stats](https://img.shields.io/nuget/dt/ZXingBlazor.svg?style=flat-square)](https://www.nuget.org/stats/packages/ZXingBlazor?groupby=Version)

[图片浏览器 Viewer](https://www.nuget.org/packages/BootstrapBlazor.Viewer#readme-body-tab) 

[手写签名 SignaturePad](https://www.nuget.org/packages/BootstrapBlazor.SignaturePad#readme-body-tab)

[定位/持续定位 Geolocation](https://www.nuget.org/packages/BootstrapBlazor.Geolocation#readme-body-tab)

[屏幕键盘 OnScreenKeyboard](https://www.nuget.org/packages/BootstrapBlazor.OnScreenKeyboard#readme-body-tab)

[百度地图 BaiduMap](https://www.nuget.org/packages/BootstrapBlazor.BaiduMap#readme-body-tab)

[谷歌地图 GoogleMap](https://www.nuget.org/packages/BootstrapBlazor.Maps#readme-body-tab)

[蓝牙和打印 Bluetooth](https://www.nuget.org/packages/BootstrapBlazor.Bluetooth#readme-body-tab)

[PDF阅读器 PdfReader](https://www.nuget.org/packages/BootstrapBlazor.PdfReader#readme-body-tab)

[文件系统访问 FileSystem](https://www.nuget.org/packages/BootstrapBlazor.FileSystem#readme-body-tab)

[光学字符识别 OCR](https://www.nuget.org/packages/BootstrapBlazor.OCR#readme-body-tab)

[电池信息/网络信息 WebAPI](https://www.nuget.org/packages/BootstrapBlazor.WebAPI#readme-body-tab)

[文件预览 FileViewer](https://www.nuget.org/packages/BootstrapBlazor.FileViewer#readme-body-tab)

[视频播放器 VideoPlayer](https://www.nuget.org/packages/BootstrapBlazor.VideoPlayer#readme-body-tab)

[图像裁剪 ImageCropper](https://www.nuget.org/packages/BootstrapBlazor.ImageCropper#readme-body-tab)

[视频播放器 BarcodeGenerator](https://www.nuget.org/packages/BootstrapBlazor.BarcodeGenerator#readme-body-tab)

#### AlexChow

[今日头条](https://www.toutiao.com/c/user/token/MS4wLjABAAAAGMBzlmgJx0rytwH08AEEY8F0wIVXB2soJXXdUP3ohAE/?) | [博客园](https://www.cnblogs.com/densen2014) | [知乎](https://www.zhihu.com/people/alex-chow-54) | [Gitee](https://gitee.com/densen2014) | [GitHub](https://github.com/densen2014)
 