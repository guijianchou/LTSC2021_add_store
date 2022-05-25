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


Note：if you are using intel 11th 12th cpu or amd Zen3 ,Microsoft 2022-5 and 2022-4 update cause windows store download apps faied with error code 0xC002001B, and ms announced new update patch KB5015020 has fixed the problem. however, ms has not delivery to all computer update channel until 22th/may, here in the download link: https://www.catalog.update.microsoft.com/Search.aspx?q=KB5015020


中文:
鉴于github上传安装包的大小限制，你可以去release页面下载商店和依赖包，或者自己手动去折腾

1.下载release安装包

2.手动折腾：

[务必注意：vclib140在电脑联网后先前会自动下载，但是2022年2月12日开始大陆屏蔽了商店和激活服务器，不仅导致数字激活无法恢复，而且商店应用下载一直出错，故在此添加了vclib的下载和安装过程。或者dns修改成4.2.2.2备用4.2.2.1，但高延迟严重影响日常使用]

打开网址：https://store.rg-adguard.net/
粘贴:https://www.microsoft.com/store/productId/9WZDNCRFJBMP
下载如下依赖包:
Microsoft.NET.Native.Framework.2.2_2.2.29512.0_x64__8wekyb3d8bbwe.Appx
Microsoft.NET.Native.Runtime.2.2_2.2.28604.0_x64__8wekyb3d8bbwe.Appx
Microsoft.UI.Xaml.2.7_7.2109.13004.0_x64__8wekyb3d8bbwe.Appx
Microsoft.VCLibs.140.00_14.0.30704.0_x64__8wekyb3d8bbwe.appx
Microsoft.WindowsStore_22202.1402.0.0_neutral___8wekyb3d8bbwe.msixbundle

3.管理员模式打开powershell,请务必按照以下安装顺序

add-appxpackage Microsoft.NET.Native.Framework.2.2_2.2.29512.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.NET.Native.Runtime.2.2_2.2.28604.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.UI.Xaml.2.7_7.2109.13004.0_x64__8wekyb3d8bbwe.Appx
add-appxpackage Microsoft.VCLibs.140.00_14.0.30704.0_x64__8wekyb3d8bbwe.appx
add-appxpackage Microsoft.WindowsStore_22202.1402.0.0_neutral___8wekyb3d8bbwe.msixbundle

Note:如果你使用的是最新11/12代intel cpu或者amd zen3 cpu，win10的4 5月更新导致应用商店下载报错0xC002001B，微软宣称最新的KB5015020已经修复了这个错误。截止2022/5/22日该补丁还全部推送，需要去windows catalog下载 https://www.catalog.update.microsoft.com/Search.aspx?q=KB5015020


