## Blazor On-screen keyboard component

English | [中文](README.zh.CN.md)



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
           placeholder="全键盘" />
 
    <input class="@ClassName"
           data-kioskboard-type="@KeyboardType.keyboard.ToString()"
           data-kioskboard-placement="@KeyboardPlacement.bottom.ToString()"
           placeholder="字母键盘" />

    <input class="@ClassName"
           data-kioskboard-type="@KeyboardType.numpad.ToString()"
           data-kioskboard-placement="@(KeyboardPlacement.bottom.ToString())"
           placeholder="数字键盘" />
    ```

4.  More informations

    Bootstrap style Blazor UI component library
Based on the Bootstrap style library, it is carefully built, and 100 a variety of commonly used components have been added to bring you an extraordinary feeling for rapid development projects

    <https://www.blazor.zone>

    <https://www.blazor.zone/onscreenkeyboards>
