# BootstrapBlazor.OnScreenKeyboard

# Blazor OnScreenKeyboard 屏幕键盘 组件

定位组件

示例:

https://blazor.app1.es/onscreenkeyboards

使用方法:

1.nuget包

```BootstrapBlazor.SignaturePad```

2._Imports.razor 文件 或者页面添加 添加组件库引用

```@using BootstrapBlazor.Components```


3.razor页面
```
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

