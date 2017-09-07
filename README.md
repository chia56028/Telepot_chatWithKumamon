Telegram Chatbot
===

## Something to Learn

### [Telegram Messenger](https://telegram.org/)
一個跨平台的即時通訊软件。可以用於傳遞訊息及任何檔案、創建一萬人的超級群組、在API上建立自己專屬的機器人...

### [Application Programming Interface（API）](https://zh.wikipedia.org/wiki/%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E6%8E%A5%E5%8F%A3)
應用程序編成接口，為銜接不同軟體系統的約定，API本身是抽象的，僅用於定義介面，不涉及應用程序在實際實現過程中的具體操作。
API提供應用程式開發人員透過軟體或硬體得以呼叫一組例程，無需知道底層原始碼及理解內部工作機制。

## Build the Project

### Goal
實作出熊本熊梗圖機器人。

### Install
在開始之前，你需要安裝一些東西：
```
# windows cmd
pip install telepot
pip install jupyter
pip install requests
pip install folium
```

### [Bot API](https://core.telegram.org/bots)
搜尋`@BotFather`，並將機器人加為好友。
![](https://i.imgur.com/8sfdikQ.png)

### Create New Bot
下`/newbot`指令，創建一個新的機器人。
照著機器人的指示，依序輸入`name`和`username`後，將會拿到一組`token`，這時你已經成功創造出一個還沒有任何功能的機器人啦。

### Create [chat_bot.ipynb](https://github.com/chia56028/Telepot_chatWithKumamon/blob/master/chat_bot.ipynb)
