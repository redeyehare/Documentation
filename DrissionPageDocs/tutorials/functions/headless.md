# Source: https://drissionpage.cn/tutorials/functions/headless

  * [](/)
  * 🥬 功能示例
  * 🥦 无头模式



# 🥦 无头模式

[![](/img/ad.png)](https://b23.tv/w62Tiqd)

要使用无头模式很简单，在`ChromiumOptions`设置`headless()`即可。
    
    
    from DrissionPage import Chromium, ChromiumOptions  
      
    co = ChromiumOptions().headless()  
    browser = Chromium(co)  
    

需要注意的是，程序结束时浏览器不会自动关闭，下次运行会继续接管该浏览器。

无头浏览器因为看不见很容易被忽视。可在程序结尾用`browser.quit()`将其关闭。
