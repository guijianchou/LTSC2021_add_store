English:
Due to github upload package size limited, I have to release all step here or u just download all required package from release page.

1. open https://store.rg-adguard.net/
2. past https://www.microsoft.com/store/productId/9WZDNCRFJBMP
3. download 64bit
Microsoft.NET.Native.Framework.2.2_2.2.29512.0_x64__8wekyb3d8bbwe.Appx
Microsoft.NET.Native.Runtime.2.2_2.2.28604.0_x64__8wekyb3d8bbwe.Appx
Microsoft.UI.Xaml.2.7_7.2109.13004.0_x64__8wekyb3d8bbwe.Appx
Microsoft.WindowsStore_22112.1401.2.0_neutral___8wekyb3d8bbwe.Msixbundle

4.run the code with powershell in order

add-appxpackage Microsoft.NET.Native.Framework.2.2_2.2.29512.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.NET.Native.Runtime.2.2_2.2.28604.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.UI.Xaml.2.7_7.2109.13004.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.WindowsStore_22112.1401.2.0_neutral___8wekyb3d8bbwe.Msixbundle


PS:
If u not connect internel after install the LTSC 2021 , you need install VClib.140 before execute the shell in step 3:
Download in the same page and install:

Microsoft.VCLibs.140.00_14.0.30704.0_x64__8wekyb3d8bbwe.appx

add-appxpackage Microsoft.VCLibs.140.00_14.0.30704.0_x64__8wekyb3d8bbwe.appx


中文:
鉴于github上传安装包的大小限制，你可以去release页面下载商店和依赖包，或者自己手动去折腾

1.下载release安装包

2.手动折腾：
打开网址：https://store.rg-adguard.net/
粘贴:https://www.microsoft.com/store/productId/9WZDNCRFJBMP
下载如下依赖包:
Microsoft.NET.Native.Framework.2.2_2.2.29512.0_x64__8wekyb3d8bbwe.Appx
Microsoft.NET.Native.Runtime.2.2_2.2.28604.0_x64__8wekyb3d8bbwe.Appx
Microsoft.UI.Xaml.2.7_7.2109.13004.0_x64__8wekyb3d8bbwe.Appx
Microsoft.VCLibs.140.00_14.0.30704.0_x64__8wekyb3d8bbwe.appx
Microsoft.WindowsStore_22202.1402.0.0_neutral_~_8wekyb3d8bbwe.msixbundle

3.管理员模式打开powershell,请务必按照以下安装顺序

add-appxpackage Microsoft.NET.Native.Framework.2.2_2.2.29512.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.NET.Native.Runtime.2.2_2.2.28604.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.UI.Xaml.2.7_7.2109.13004.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.VCLibs.140.00_14.0.30704.0_x64__8wekyb3d8bbwe.appx
add-appxpackage Microsoft.WindowsStore_22202.1402.0.0_neutral_~_8wekyb3d8bbwe.msixbundle




