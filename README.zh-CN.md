## Blazor OnScreenKeyboard 屏幕键盘 组件

[English](README.md) | 中文


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
